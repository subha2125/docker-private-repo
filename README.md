** Private Repo ***
---------------------------

Download Registry and docker-regsitry-ui image and run . refer to C:\Users\eshghos\Downloads\Docs\Project\docker-registry

Tag an image

docker tag <image-name>:tag hostname:port/username/<image-name>:tag
docker tag eureka:latest localhost:5000/eshghos/eureka:latest

Then push to private repo

docker push hostname:port/username/<image-name>:tag
docker push localhost:5000/eshghos/eureka:latest

Access private repo GUI via -- http://localhost:8080/repositories/