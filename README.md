# prometheus-federation

This is repository has two configure for make a cluster of prometheus federation. 


## Instalation

 First edit ingress in each deployment, also to edit the "job federation" on the prometheus leader.
 
 ```
 kubectl apply -f prometheus-development.yaml -n younamespace
 
 ```
