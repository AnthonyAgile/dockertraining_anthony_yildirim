docker build -f "c:\code\dockertraining_anthony_yildirim\dockertraining_anthony_yildirim\Dockerfile" --force-rm -t site_image "c:\code\dockertraining_anthony_yildirim"
docker images
docker run --name Site1 -p 8085:80 site_image
start http://localhost:8085/ #open a browser from cmd

docker build -f "c:\code\dockertraining_anthony_yildirim\dockertraining_anthony_yildirim\Dockerfile" --force-rm -t site_image "c:\code\dockertraining_anthony_yildirim"
docker images
docker run --name Site2 -p 8086:80 site_image
start http://localhost:8086/ #open a browser from cmd
