## network    
   
     docker network create --attachable -d bridge onlinestore


## in compose folder

     $ docker run --entrypoint htpasswd \
        httpd:2 -Bbn userregistry userpassword > htpasswd

## login 

     docker login registry.digitallab.academy:5001