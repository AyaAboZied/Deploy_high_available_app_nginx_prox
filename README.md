# Deploy_high_available_app_nginx_prox
Deploy high available app with nginx &amp; proxy using terraform modules

Create vpc that have 2 public Ec2 run nginx
Use Elastic load balancer to distribute traffic between then 
connect with private Elastic load balancer that distribute traffic between 2 private Ec2 have Apache Server 




## Run Terraform Steps:

> 1. initialize:

```
terraform init
```
> 2. Apply:
```
terraform apply
```
## Archticture:

![Screenshot from 2023-02-05 00-34-38](https://user-images.githubusercontent.com/68289149/216792328-5f2cc954-ebc7-43f4-92e9-3d5cf839c9ed.png)
