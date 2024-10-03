# microservices-config-repo

Config Server sẽ tìm file cấu hình theo cú pháp:

{application-name}-{profile}.yml

VD:
user-service.yml: Dành cho user-service với profile mặc định.
user-service-dev.yml: Dành cho user-service với profile dev.
application.yml: Cấu hình chung áp dụng cho tất cả các service.