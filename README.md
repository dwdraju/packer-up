# Getting started with Packer

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/c2698f0185654933aae1591f4503dc35)](https://app.codacy.com/app/dwdraju/packer-up?utm_source=github.com&utm_medium=referral&utm_content=dwdraju/packer-up&utm_campaign=Badge_Grade_Settings)

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
