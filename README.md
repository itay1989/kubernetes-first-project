# kubernetes-first-project

note: this project was created with docker desktop without minikube. so if you run it with minikube check the minikube ip to view the project with browser , use the minikube ip . 

1. clone this project : git clone https://github.com/itay1989/kubernetes-first-project.git
2. in your terminal/cmd ............ 
3. you will need to grant premissions to ingress service in your local machine to be able to get traffic.
visit this page https://kubernetes.github.io/ingress-nginx/deploy/#docker-for-mac to get more info . 
4. the above step can be followed by this command : kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.45.0/deploy/static/provider/cloud/deploy.yaml . run it in the terminal/cmd
5. postgres needs a password to work so use this command to create your pg password : kubectl create secret generic pgpassword --from-literal PGPASSWORD=yourpassword 
