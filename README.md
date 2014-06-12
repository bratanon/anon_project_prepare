# web_project_prepare

A script to prepare a simple web project.

It will:

* Creates a directory in `/var/www` with the name of the project.
* Creates a vhost file for apache from the provided `vhost.template` file.
* Adds an entry int he host file.
* Download Drupal core to the projects www directory *(optional)*.
* Creates a mysql database with the project name *(optional)*.


## Run

```shell
> web_project_prepare [PROJECT NAME]
```
