# Docker-01-fundamental
This repository is used for docker fundamental 
 2 python  --version                                                                                                   
   3 pip install -r .\requirements.txt                                                                                   
   4 python app.py                                                                                                                             
  10 clear                                                                                                               
  11 docker build . -t demodockerapp:v1.0                                                                                
  12 docker images                                                                                                       
  13 docker run -p 5001:5000 demodockerapp:v1.0                                                                          
  14 docker run -p 5005:5000 demodockerapp:v1.0                                                                          
  15 docker run -d -p 5005:5000 demodockerapp:v1.0                                                                       
  16 docker ps                                                                                                           
  17 docker stop fae57723c04e                                                                                            
  18 docker images                                                                                                       
  19 docker run -p 5001:5000 7f42c6e93c17                                                                                
  20 docker run -d  -p 5001:5000 7f42c6e93c17                                                                            
  21 docker login                                                                                                        
  22 docker logout                                                                                                       
  23 docker login                                                                                                        
  24 docker images                                                                                                       
  25 docker tag 7f42c6e93c17 mk86gaur/mkg-flask-app:v01                                                                  
  26 docker images                                                                                                       
  27 docker push mk86gaur/mkg-flask-app:v01                                                                              
  28 docker tag 7f42c6e93c17 mk86gaur/mkg-flaskapp:v01                                                                   
  29 docker images                                                                                                       
  30 docker push mk86gaur/mkg-flaskapp:v01                                                                               
  31 docker build -t demodockerapp:v2.0                                                                                  
  32 docker build -t demodockerapp:v2 .                                                                                  
  33 docker images                                                                                                       
  34 docker tag demodockerapp:v2  mk86gaur/mkg-flaskapp:v02                                                              
  35 docker image                                                                                                        
  36 docker images                                                                                                       
  37 docker push mk86gaur/mkg-flaskapp:v02                                                                               
  38 docker rm mk86gaur/mkg-flaskapp:v02                                                                                 
  39 docker image rm mk86gaur/mkg-flaskapp:v02                                                                           
  40 docker images                                                                                                       
  41 docker pull mk86gaur/mkg-flaskapp:v02                                                                               
  42 docker images                                                                                                       
  43 docker build -t demodockerapp:dev .                                                                                 
  44 docker image                                                                                                        
  45 docker images                                                                                                       
  46 docker tag demodockerapp:dev mk86gaur/mkg-flaskapp:dev                                                              
  47 docke images                                                                                                        
  48 \docker images                                                                                                      
  49 docker images                                                                                                       
  50 docker tag demodockerapp:dev mk86gaur/mkg-flaskapp-dev                                                              
  51 dcoker images                                                                                                       
  52 docke push mk86gaur/mkg-flaskapp-dev:dev                                                                            
  53 docker push mk86gaur/mkg-flaskapp-dev:dev                                                                           
  54 docker images                                                                                                       
  55 docker images rm d4da583d5b3d                                                                                       
  56 docker images                                                                                                       
  57 docker images rm demodockerapp:dev mk86gaur/mkg-flaskapp-dev:latest                                                 
  58 docker images rm demodockerapp:dev                                                                                  
  59 docker images rm  mk86gaur/mkg-flaskapp-dev:latest                                                                  
  60 docker rmi d4da583d5b3d                                                                                             
  61 docker image rm  mk86gaur/mkg-flaskapp-dev:latest                                                                   
  62 docker image rm  demodockerapp:dev                                                                                  
  63 docker images                                                                                                       
  64 docker build -t demodockerapp-dev                                                                                   
  65 docker build -t demodockerapp-dev .                                                                                 
  66 docker images                                                                                                       
  67 docker tag demodockerapp-dev:latest mk86gaur/mkg-flaskapp-dev:dev                                                   
  68 docker images                                                                                                       
  69 docker push mk86gaur/mkg-flaskapp-dev:dev                                                                           
  70 git --version                                                                                                       
  71 git config --global user.name "manojkumargaur-123"                                                                                
  75 git config --global user.email "manojkumargaur86@gmail.com"                                                                        
  77 git config --list                                                                                                   
  78 git init                                                                                                            
  79 git status                                                                                                          
  80 git add .                                                                                                           
  81 git commit -m "Initial docker fundamental"                                                                          
  82 git remote add origin https://github.com/manojkumargaur-123/Docker-01-fundamental.git                               
  83 git branch -M main                                                                                                  
  84 git push -u origin main                                                                                             
  85 git pull origin main --allow-unrelated-histories                                                                    
  86 git log --oneline     
on powershall 
 Id CommandLine
  -- -----------
   1 git status
   2 cd "D:\herovired\docker\Practice\Docker 01"
   3 git status
   4 git push -u origin main

  
