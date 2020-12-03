# To use this module, add the following variables into your block module code

module "vpc" {
  source = "./modules/chris/aws-simple-vpc"

  vpc_name = "<VPC NAME>"
  cidr = "<VPC_CIDR>"
}
