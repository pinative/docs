# Guideline of the PiNative Alpha Version 


### 1. Link your container registry
1. Go to **Settings** from left menu, and click the <strong>LINKS</strong> tab
![Image](img/alpha/links.png)

2. Create a new LINK by click the **ADD LINK** button
![Image](img/alpha/add-link.png)
>**Link Type** - Choose the Docker Hub.<br>
>**Name** - Give a name for this link.<br>
>**Registry URL** - The container registry URL e.g.https://registry.pinative.io/v2/, by default it's the docker hub.<br>
>**Account** - Your container registry account name.<br>
>**Secret** - Your container registry password, **ONLY** setup this if you would like deploy private images.


### 2. Deploy your APPLICATION 
**NOTE** You have to make sure that the container registry was configed succeeded.

1. Go to **Deployments** from left menu
![Image](img/alpha/deployment-list.png)

2. Deploy a new app by click the **NEW DEPLOYMENT** button
![Image](img/alpha/new-deployment.png)
>**Deployment Name** - Give a unique name for this deployment, e.g. web-app<br>
>**Minimum Replicas** - The minimum number of podlets you would like to create.<br>
>**Maximum Replicas** - The maximum number of podlets you would like to create<br>
>**Lables** - The labels of your current deployment, e.g. app:web, maximum 5 lables you can have.<br>
>**Image** - Choose an Image you want to deploy.<br>
>**Image Tag** - Choose a Tag/Version of the image you've chosen.<br>
>**Container Name** - Give the container a name.<br>
>**Container Port** - The Container Port to be used, your EXPOSED APPLICATION PORT.<br>
>**CPU Request** - The minimum CPU this deployment to be used.<br>
>**CPU Limit** - The maximum CPU this deployment to be used.<br>
>**Memory Request** - The minimum Memory this deployment to be used.<br>
>**Memory Limit** - The maximum Memory this deployment to be used.<br>

3. Act on your deployed apps

Once you deployed an app succeeded, you can get it from the **Deployments**
![Image](img/alpha/deployment-list1.png)
The Actions you could do
>Modify the deployment by click ![Image](img/alpha/edit.png).<br>
>Delete the deployment by click ![Image](img/alpha/remove.png).<br>
>Access the application by click ![Image](img/alpha/launch.png).<br>
