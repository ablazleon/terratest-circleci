# terratest-circleci

The purpose of the repo is to ilustrate and check how to write a .config file for circleci to run Terratest tests. There was not found any demo terratest .config file so following [this comment](https://github.com/gruntwork-io/terratest/issues/265) [this module](https://github.com/influxdata/terraform-aws-influx/blob/v0.2.0/.circleci/config.yml) is modified and check using an example of [terratest](https://github.com/gruntwork-io/terratest).

- First, it is modifeid this based .config file, first adding the credentials to circle ci.



--------------

- [terraform-aws-s3-example](https://github.com/gruntwork-io/terratest/blob/master/examples/terraform-aws-s3-example/main.tf), [checks](https://github.com/gruntwork-io/terratest/blob/master/test/terraform_aws_s3_example_test.go) that many properties desired in the creation appears in the bucket resulted.
- [terraform-aws-example](https://github.com/gruntwork-io/terratest/tree/master/examples/terraform-aws-example) ,[checks](https://github.com/gruntwork-io/terratest/blob/master/test/terraform_aws_example_test.go) the tag that the instance tag, owns the name that it is given as a variable.
- [terraform-ssh-example](https://github.com/gruntwork-io/terratest/blob/master/examples/terraform-ssh-example/main.tf), [checks](https://github.com/gruntwork-io/terratest/blob/master/test/terraform_ssh_example_test.go) that it can be connceted to a public and a private instance, checking that the echo of what it is output is what it is input.
