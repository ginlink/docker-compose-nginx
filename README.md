docker run -d -p 80:80 \
 -v /Users/jiangjin/Documents/docker/nginx/nginx.conf:/etc/nginx/nginx.conf:ro \
 -v /Users/jiangjin/Documents/docker/nginx/dist:/dist \
 --name my-nginx \
 nginx:latest
