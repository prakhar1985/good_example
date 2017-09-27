main.yaml
 
#Step 1: Deploy Insfrastructure on OSP 10
-Variables to be set in respective files

>roles/osp-instances/frontend.yaml
```
instance_name: frontend
group: frontends
deployment: dev
```

>roles/osp-instances/app1.yaml
```
instance_name: app1
group: apps
deployment: dev
```

>roles/osp-instances/app2.yaml
```
instance_name: app2
group: apps
deployment: dev
```

>roles/osp-instances/db.yaml
```
instance_name: db
group: appdbs
deployment: dev
```
#Step 2: Configure Instances 

#Step 3: Deploy example APP
