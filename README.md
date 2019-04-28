Deployed web application on tomcat -> kubernetes cluster on google cloud.

Git hub URL: https://github.com/sapnakrishnan1987/devopshello

Application URL: http://104.198.239.226/hello/
The application is load balanced and deployed on 2 kub pods for failover.The application was packaged using ant and a war was created and pushed to GIT. 
The application was then dockerized using Dockerfile and the image was pushed in google image registry.

The prometheus is deployed on the same cluster to scrape metrics from application.

