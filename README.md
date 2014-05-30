# web_project_prepare

A script to prepare a simple web project.

It will:

* Create a directory in `/var/www` with the name of the project.
* Create a vhost file for apache from the provided `template.conf` file.
* Add en entry int he host file.
* Download Drupal core to the projects www directory *(optional)*.


## Run

```shell
> web_project_prepare [PROJECT NAME]
```
