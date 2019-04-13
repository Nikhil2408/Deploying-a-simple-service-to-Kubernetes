# Deploying a simple service to Kubernetes

<h3>Task:</h3>

Suppose a team manages an online storefront. They want a simple service in their kubernetes cluster that is able to provide a list of products. One pod will use this service to access the service's pods. Deploy the service's pods to the cluster and create a k8s service to provide access to all the service's pods. Deploy 4 replicas of the service pod.

We already have a public Docker image for the store-product app provided by LinuxAcademy- <b>linuxacademycontent/store-products:1.0.0</b>

<p align="center">
  <img src="https://github.com/Nikhil2408/Demo/blob/master/images/service%20in%20k8s.png">
</p>
