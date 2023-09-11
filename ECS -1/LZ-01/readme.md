Terraform module to provision an ECS instance

terraform {
}

provider "alicloud"{
  region     = "ap-southeast-1"
}

module "module" {
       source = ".//terraform_ecs.git"
       instance type = ecs.t5-lc2m1.nano"
}