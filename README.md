# Deploy_high_available_app_nginx_prox
Deploy high available app with nginx &amp; proxy using terraform modules

Create vpc that has 4 Ec2 two in a public subnet that contains nginx with ALB to load balancing between them and they send a signal to the new ALB to load balancing between the 2 private Ec2  that have Apache




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
