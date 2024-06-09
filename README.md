# frrape
# refrence repos
# docker:
https://github.com/frappe/frappe_docker
# helm: 
https://github.com/frappe/helm/tree/main
# hrms: 
https://github.com/frappe/hrms

# 1. Custom Frappe HR Application
  to install locally there is to ways
  hard way => follow this guide https://codewithkarani.com/2023/12/31/how-to-install-erpnext-version-15-in-ubuntu-a-step-by-step-guide/
  by docker => follow this guide https://medium.com/@josephcastillo_82888/simplifying-the-installion-of-erpnext-15-hrms-15-and-any-custom-apps-with-docker-49784f403d18

# 2. Docker Containerization:
   useing the docker repo write your Docker file then build your image
   you can find my image at => https://hub.docker.com/repository/docker/mohamedtarekelsayed/frappe/general

# 3. Helm Chart Modification
   using helm repo navigate to erpnext dir and edit values.yml file with your own image

# 4. Deployment:
    navigate to erpnext dir then run
      helm install erpnext .
    verify that the chart has been installed successfully by running
     helm ls
     kubectl get all
     

