# Getting started with Packer
#### Validate Packer template
```
packer validate build.json
```

#### Buid image
```
packer build \
    -var 'aws_access_key=YOUR ACCESS KEY' \
    -var 'aws_secret_key=YOUR SECRET KEY' \
    build.json
```    