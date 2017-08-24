# Managing Datadog with Terraform example

Shows how to use Terraform to manage Datadog:

- Create monitors
- Create timeboards and graphs
- Share queries and thresholds across monitors and graphs

How to run:

- [Install Terraform](https://www.terraform.io/downloads.html)
- Run the following:

``` sh
$ git clone https://github.com/travisjeffery/datadog-terraform-example.git
$ cd datadog-terraform-example
$ terraform init
$ terraform plan # You'll be asked to input your Datadog API and APP keys
$ terraform apply
```

## License

MIT

--- 

- [travisjeffery.com](http://travisjeffery.com)
- GitHub [@travisjeffery](https://github.com/travisjeffery)
- Twitter [@travisjeffery](https://twitter.com/travisjeffery)
- Medium [@travisjeffery](https://medium.com/@travisjeffery)

