# infracodetesting

```

This document introduces Test Driven Development of Ansible and Terraform Codes

Understanding what is Test Driven Development
https://www.youtube.com/watch?v=dWayn0QsJr8

Understanding TDD through Easy C# Code Example
https://www.youtube.com/watch?v=l4xhTq4qmC0

Understanding concepts behind Infrastructure as Code Testing
https://www.infoq.com/presentations/automated-testing-terraform-docker-packer/

Understand how to use Rspec based methods to Test Infrastructure as Code
https://www.youtube.com/watch?v=aV_DP7GhBHM


Ansible Testing
---------------------
There are two ways - 1. Molecule 2. Test-Kitchen with ServerSpec

Ansible Testing with Molecule
-------------------------------
Introduction to Molecule (no need to follow steps, just watch to understand the concept of ansible testing)
https://www.ansible.com/practical-ansible-testing-with-molecule

Introduction to Goss
https://github.com/aelsabbahy/goss

Ansible Testing using Molecule and Goss
https://linora-solutions.nl/post/testing_ansible_roles_with_molecule_goss_and_docker/

Introduction to TestInfra
https://testinfra.readthedocs.io/en/latest/

How to use molecule with testinfra for testing ansible/0
https://www.digitalocean.com/community/tutorials/how-to-test-ansible-roles-with-molecule-on-ubuntu-16-04


Ansible Testing using Test-Kitchen and ServerSpec
------------------------------------------------------

Understand ServerSpec - An independent local testing tool for testing what's there in a server
https://debian-administration.org/article/703/A_brief_introduction_to_server-testing_with_serverspec

Resource types in ServerSpec
https://serverspec.org/resource_types.html

Understanding Inspec
http://www.anniehedgie.com/inspec-basics-1

Detailed Inspec Tutorials
https://www.inspec.io/tutorials/

ServerSpec vs Inspec
https://medium.com/@Joachim8675309/serverspec-vs-inspec-17272df2718f

What is Vagrant
https://www.taniarascia.com/what-are-vagrant-and-virtualbox-and-how-do-i-use-them/

Understanding Vagrantfile
http://devopspy.com/devops/vagrantfile-explained/

Understanding Chef Test Kitchen
https://www.tutorialspoint.com/chef/chef_test_kitchen_setup.htm

How to use ServerSpec with Test-Kitchen
https://alexharv074.github.io/2016/05/25/testing-an-ansible-role-using-test-kitchen.html
https://www.rubydoc.info/gems/kitchen-ansible/0.0.30#Test-Kitchen_Serverspec


Terraform Testing
--------------------
There are three main ways to test Terraform code. None of them are as easy as Goss. Hence take on the terraform testing only after you have gone through Ansible testing (all options, step by step) thoroughly). It is complex because you are not having an operating system being managed through terraform, instead you have a cloud. So all the serverspec, inspec things are not going to work. So its a bit different.
1. Raw use of Go language to test Terraform code
2. Gruntworks is a company which created a Go language library of pre built functions to test Terraform code. They named it Terratest and then opensourced it
3. Test-Kitchen can be used for testing terraform code as well but it is under development

TDD of Terraform with Go Language
https://medium.com/@joatmon08/test-driven-development-techniques-for-infrastructure-a73bd1ab273b

TDD of Terraform using TerraTest
https://blog.octo.com/test-your-infrastructure-code-with-terratest/

Learn TerraTest through Examples
https://github.com/gruntwork-io/terratest/tree/master/examples

Using Test Kitchen for Terraform Testing
https://github.com/newcontext-oss/kitchen-terraform
https://newcontext-oss.github.io/kitchen-terraform/tutorials/amazon_provider_ec2.html
https://newcontext-oss.github.io/kitchen-terraform/tutorials/


```
