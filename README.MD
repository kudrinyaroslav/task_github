
GITHUB CITIES 
===

Application which helps you add cities in database
and get them using easy way through browser
---


* To add new city to database you have to put following command in shell:

curl http://IP_Address:ingress-nginx-controller_NodePort/add -X POST -d '{"city":"New-York"}' -H 'Content-Type: application/json'



* To get city list:

curl http://IP_Address:ingress-nginx-controller_NodePort/all


* to get IP Address look at you cluster IP
* to get ingress-nginx-controller NodePort in cluster do following kubectl get svc -n ingress-nginx