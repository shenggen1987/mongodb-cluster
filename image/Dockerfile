FROM mongo
#将秘钥文件复制到镜像中
COPY auth.key /app/auth.key
RUN chown -R mongodb:mongodb /app/auth.key
#设置秘钥文件权限，这一步非常关键
RUN chmod 600 /app/auth.key