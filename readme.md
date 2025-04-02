Create the Cluster on GCP. Diploy the wordpress application and MySQL for DB. Wordpress should connect to Db and Storage should be PV and PVC(Dynamic Storage).

1. Create the k8s Cluster on GCP
2. Create the manifeast files for
    1. Wordpress Deployment
    2. MySQL Deployment
    3. Storage Class
    4. PVC for both Deployment
    5. Netpol for Wrodpress and MySQL
    6. Create the Service (Cluster IP and NodePort)
3. Once Deploy, Application should connect from web.
