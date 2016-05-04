![](https://raw.github.com/alacner/pecan-web/master/docs/logo.jpg)

Pecan - A On-line Deployment Tool

Now, there are more than hundreds of companies hosted walle for deployment, star pecan if you like : )

* Support git/svn Version control system.
* User signup by admin/develop identity.
* Developer submit a task, deploy task.
* Admin audit task.
* Multiple project.
* Multiple Task Parallel.
* Quick rollback.
* Group relation of project.
* Task of pre-deploy（e.g: test ENV var）.
* Task of post-deploy（e.g: mvn/ant, composer install for vendor）.
* Task of pre-release（e.g: stop service）.
* Task of post-release（e.g: restart service）.
* Check up file md5.
* Multi-process multi-server file transfer (Ansible).
* Configuration center (replace files or autoconf)


Requirements
------------

* Bash(git、ssh)
* LNMP/LAMP(php5.4+)
* Ansible(Optional)
* Autoconf(Optional)

That's all. It's base package of PHP environment!


Installation
------------
```
git clone git@github.com:alacner/pecan-web.git
cd pecan-web
```

## CHANGELOG
[CHANGELOG](https://github.com/alacner/pecan-web/releases)


Discussing
----------
- [submit issue](https://github.com/alacner/pecan-web/issues/new)
- email: alacner@tfizzy.org
