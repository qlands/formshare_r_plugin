# Formshare R Plug-in
A FormShare plug-in that provides examples for using FormShare's R Package

- FormShare >= 2.22.0
- FormShare Analytics Plug-in: (https://github.com/qlands/formshare_analytics_plugin)
- FormShare Remote SQL Plug-in: ([https://github.com/qlands/formshare_sql_plugin](https://github.com/qlands/formshare_sql_plugin))
- FormShare R Package: ([https://cran.r-project.org/web/packages/FormShare](https://cran.r-project.org/web/packages/FormShare))



Getting Started
---------------

- Activate the FormShare environment.

```
$ . ./path/to/FormShare/bin/activate
```

- Change directory into your newly created plugin.

```
$ cd remoteSQL
```

- Build the plugin

```
$ python setup.py develop
```

- Add the plug-in to the FormShare list of plug-ins by editing the following line in development.ini or production.ini

```
    #formshare.plugins = examplePlugin
    formshare.plugins = remoteSQL
```

- Run FormShare again
