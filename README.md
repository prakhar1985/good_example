main.yaml
 
Step 1: Deploy Insfrastructure on OSP 10

>roles/osp-instances/vars/frontend.yaml
```
instance_name: frontend
group: frontends
deployment: dev
security_group_name: frontend_servers
```

>roles/osp-instances/vars/app1.yaml
```
instance_name: app1
group: apps
deployment: dev
security_group_name: app_servers
```

>roles/osp-instances/vars/app2.yaml
```
instance_name: app2
group: apps
deployment: dev
security_group_name: app_servers
```

>roles/osp-instances/vars/db.yaml
```
instance_name: db
group: appdbs
deployment: dev
security_group_name: db_servers
```
Step 2: Configure Instances 

Step 3: Deploy example APP
