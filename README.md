## What is terraform

Terraform provides a common configuration to launch infrastructure — from physical and virtual servers to email and DNS providers. Once launched, Terraform safely and efficiently changes infrastructure as the configuration is evolved.

Simple file based configuration gives you a single view of your entire infrastructure.

[https://www.terraform.io/](https://www.terraform.io/)

## Dockerfile

This Docker image is based on the official [alpine:3.4](https://hub.docker.com/_/alpine/) base image.

## How to use this image

```
TBC

```

## Using

**Please note: Create by your Terraform configuration files (.tf) is `/data` directory**

### terraform apply

```
docker run --rm -v /data:/data yourname/terraform apply [options]
```

### terraform destroy

```
docker run --rm -v /data:/data yourname/terraform destroy [options] [DIR]
```

### terraform fmt

```
docker run --rm -v /data:/data yourname/terraform fmt [options] [DIR]
```

### terraform force-unlock

```
docker run --rm -v /data:/data yourname/terraform force-unlock LOCK_ID [DIR]
```

### terraform get

```
docker run --rm -v /data:/data yourname/terraform get [options] PATH
```

### terraform graph

```
docker run --rm -v /data:/data yourname/terraform graph [options]
```

### terraform import

```
docker run --rm -v /data:/data yourname/terraform [options] ADDR ID
```

### terraform init

```
docker run --rm -v /data:/data yourname/terraform init [options] SOURCE [PATH]
```

### terraform output

```
docker run --rm -v /data:/data yourname/terraform output [options] NAME
```

### terraform plan

```
docker run --rm -v /data:/data yourname/terraform plan [options]
```

### terraform providers

```
docker run --rm -v /data:/data yourname/terraform providers [config-path]
```

### terraform push

```
docker run --rm -v /data:/data yourname/terraform push [options]
```

### terraform refresh

```
docker run --rm -v /data:/data yourname/terraform refresh [options]
```

### terraform show

```
docker run --rm -v /data:/data yourname/terraform show terraform.tfstate [options]
```

### terraform state <subcommand> [options] [args]

```
docker run --rm -v /data:/data yourname/terraform state <subcommand> [options] [args]
```

### terraform taint

```
docker run --rm -v /data:/data yourname/terraform taint [options] name
```

### terraform untaint

```
docker run --rm -v /data:/data yourname/terraform untaint [options] name
```

### terraform validate

```
docker run --rm -v /data:/data yourname/terraform validate
```

### terraform version

```
docker run --rm yourname/terraform version
```

### terraform workspace

```
docker run --rm yourname/terraform workspace <subcommand> [options] [args]
```
