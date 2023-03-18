# Wordpress Environment
> Môi trường cài đặt wordpress

[![Build Status][travis-image]][travis-url]

One to two paragraph statement about your product and what it does.

![](https://i0.wp.com/wordpress.org/files/2023/03/swag-bulk-org.png?resize=768%2C636&ssl=1)

## Installation

Windows & Linux:

```sh
docker-compose up
```

## Hướng dẫn depoy source lên server

- Export volumes wordpress_resource ra máy host, đẩy resource này lên server

- Export database từ phpMyAdmin, import database *.sql này lên server

## Hướng dẫn depoy source local

- Volumes resource trực tiếp vào container của docker nếu dev trên windows tránh lỗi delay
- Volumes wordpress_resource => ./wordpress_resource đẩy ra host nếu dev trên linux

## Extension cài thêm

* Docker windows
    * Volumes Backup & Share: https://hub.docker.com/extensions/docker/volumes-backup-extension
* Images
    * phpMyAdmin

------------------------------------- Khang Design Resource ❤️❤️

