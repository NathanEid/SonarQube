# SonarQube

### Lab Day 01

#### Install SonarQube with helm

    git clone https://github.com/kareemelkasaby1/Sonarqube-Demo.git
    helm create postgress
    helm create sonarqube
    helm install postgress ./postgress/
    helm install sonarqube ./sonarqube/
  
![image](https://user-images.githubusercontent.com/40915944/217374706-05b4605f-6814-43e5-8f4c-5677a11cb4c7.png)
![image](https://user-images.githubusercontent.com/40915944/217374819-1934579a-0b94-4c35-be89-ba919a3fd312.png)
![image](https://user-images.githubusercontent.com/40915944/217375073-939c9de3-43b1-4811-a37f-962c9c303d98.png)


#### Apply Jenkins on K8S useing Helm to deploy

    helm create jenkins
    helm install jenkins ./jenkins/
    
![image](https://user-images.githubusercontent.com/40915944/217377852-053af4d2-fe76-4335-a4b7-40f94809d63f.png)
![image](https://user-images.githubusercontent.com/40915944/217378080-a94a9e10-bf44-4382-bb06-a90d412e7088.png)
![image](https://user-images.githubusercontent.com/40915944/217378502-e060fe83-ad9c-499c-a4cc-adf014641a13.png)
![image](https://user-images.githubusercontent.com/40915944/217380348-026f230e-6e85-4b41-82c9-36667b5c2dbb.png)

#### integrate SonarQube with Jenkins 

![image](https://user-images.githubusercontent.com/40915944/217384540-b62a523e-c2e5-476e-bfcd-4e10d864f14f.png)
![image](https://user-images.githubusercontent.com/40915944/217384984-4d5f6df9-1e4c-4410-aaa0-72e21ade9a9c.png)
![image](https://user-images.githubusercontent.com/40915944/217390073-95fd6dfb-08b2-4c75-91ca-f57469ef28c1.png)
![image](https://user-images.githubusercontent.com/40915944/217390545-9a0f6871-2994-4a6a-86d2-a65e23ea62e1.png)
![image](https://user-images.githubusercontent.com/40915944/217391468-12f9f4bd-90d8-4705-b97d-2089ebd7bdf3.png)
![image](https://user-images.githubusercontent.com/40915944/217392493-05493a9b-cefd-4e4e-8520-fb085f50bdda.png)

#### Multibranch Pipline

![image](https://user-images.githubusercontent.com/40915944/217396697-f7d2723d-613f-41bd-9d07-de17946ed28a.png)
![image](https://user-images.githubusercontent.com/40915944/217396495-f6a54a72-767b-4177-907a-13a9d0365fc6.png)

