# rails_angular_demo

## Tạo mới dự án rails
```
cafe@ubuntu:~/projects$ rails new rails_angular_demo
```

## Tạo api users đơn giản
```
cafe@ubuntu:~/projects/rails_angular_demo$ rails g scaffold user name:string
```

## Tạo app client
```
cafe@ubuntu:~/projects/rails_angular_demo/client$ yo angular
```
## Thiết lập proxy dùng grunt-connect-proxy
```
npm install --save-dev grunt-connect-proxy
```
## Build client app
```
grunt build
```