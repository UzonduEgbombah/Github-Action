## Familiarising With Docker-Action

- I created an ec2 instance t2.large and modified my ec2 volume to 20gb

- I installed Git and Docker

![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/5697429c-c706-415c-9c74-6e5b3dd9c47d)


- I installed sonarqube with Docker and mapped it to port 9000 which is specifically for sonarqube

![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/16f60afb-842e-4a50-8ecc-019e5e355417)


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/68d7a9ef-dde9-4be3-8a51-ac7c45389b49)
 

- I ran the Docker image


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/a1440f77-620c-4507-9c4d-93b0e46ed1ef)


- Search on the web with the <public-ip:9000> 


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/90e4dbc0-15c0-4707-9143-2d14e97fbca8)


- I generated a user token in sonarqube which would be used as an authenticator by github and also kept as a secret  


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/ffae7f75-1c1e-4407-976e-0075f896788a)


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/d550b06d-c424-458f-82f1-100cf82de398)


- The sonarqube url was saved as a secret too.


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/9a6575aa-d5bf-4d18-ad92-273fd2d43150)


- The .yaml file for the workflow, full script saved in my repo.


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/950a41a9-3f48-487b-9118-65b296bb4dd8)


- Pushed to my repo to trigger a build.


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/ae01a416-bc59-4a71-a069-b01a21441cc8)



- Build ran successfully, though i encountered some errors which i later resolved


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/be392b71-0e9c-46fa-8554-84443e72bf8e)


- So the script was built with github-action and the code with sonarqube was scanned 


![](https://github.com/UzonduEgbombah/Github-Action/assets/137091610/9af5224f-9f02-46e0-aceb-fae5ba13e38c)



