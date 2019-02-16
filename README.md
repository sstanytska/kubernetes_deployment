# A. Create a deployment:  
-- Name: nginx-app  
-- Using conteiner: nginx:1.14.0  
-- The deployment should contain 5 replicas  
Next, update the app 1.15.1 by performing a rolling update, and record that update  
FInally, rollback that udate to the previous version  
Records rollout commands into rollout-steps.txt file

# B. Launch 3 replicas of the nginx image with the label: app_runtime_stage=staging. Deployment name: nginx-deploy

# C. Scale the deployment nginx-deploy

# D. Create group of apps which serve WordPress:  
--- Deployment:  
-- NAme: wordpress-deploument  
-- 3 replicas  
-- USe wordpress image  

--- MySQL ReplicaSet:  
-- Name: mysql-rs  
-- 1 replica  
-- Use mysql image  
-- Use PersistentVolume  

--- Expose Wordpress using LoadBAlancer service
