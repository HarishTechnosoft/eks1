#created VPC and make sure before trying to create should configure aws config access keuy and secreate key

provider "aws"{
    region = "us-east-1"
}

resource "aws_vpc" "my-vpc" {
    cidr_block = "10.0.0.0/16"

}