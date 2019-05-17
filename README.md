# Getting started with Packer
## Validate Packer template
```console
packer validate build.json
```

## Buid image
```console
packer build \
    -var 'aws_access_key=YOUR ACCESS KEY' \
    -var 'aws_secret_key=YOUR SECRET KEY' \
    build.json
```    
