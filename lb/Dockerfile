FROM nginx:alpine

ADD loadbalancer.conf /etc/nginx/conf.d
# daemon offでフォアグラウンド実行を指定
CMD ["nginx", "-g", "daemon off;","-c","/etc/nginx/nginx.conf"]