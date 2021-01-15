# Practical-DevOps-Second-Edition
Practical DevOps Second Edition, published by Packt
This is the code repository for [Practical DevOps - Second Edition](https://www.packtpub.com/virtualization-and-cloud/practical-devops-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788392570), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Virtual and ADevOps is a practical field that focuses on delivering business value as efficiently as possible. DevOps encompasses all code workflows from testing environments to production environments. It stresses cooperation between different roles, and how they can work together more closely, as the roots of the word imply—Development and Operations.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
---
- hosts: localhost
 vars:
 http_port: 80
 max_clients: 200
 remote_user: root
 tasks:
 - name: ensure apache is at the latest version
 yum: name=httpd state=latest
```

This book contains many practical examples. To work through the examples, you need a
machine preferably with a GNU/Linux-based operating system, such as Fedora.

## Related Products
* [Mastering Chef the DevOps Way by School of DevOps® [Video]](https://www.packtpub.com/virtualization-and-cloud/mastering-chef-devops-way-school-devops®-video?utm_source=github&utm_medium=repository&utm_campaign=9781789345704)

* [Mastering Puppet the DevOps way by School of DevOps® [Video]](https://www.packtpub.com/virtualization-and-cloud/mastering-puppet-devops-way-school-devops®-video?utm_source=github&utm_medium=repository&utm_campaign=9781789340921)

* [Mastering Docker (2017) the DevOps way by School of Devops® [Video]](https://www.packtpub.com/networking-and-servers/python-penetration-testing-essentials-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789138962)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
