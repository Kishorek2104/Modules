terraform {
  required_providers {
    aws = {
        source = "hashicorp/aws"
    }
  }
}

resource "aws_instance" "EC2" {
  ami = var.ami
  instance_type = "t2.micro"
}

variable "ami" {}
