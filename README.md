M Morgan Textiles
=================

## Dependencies
- a local server running apache and PHP >= 5.3.0, with a vhost entry similar to the following
- node.js
- npm
- hosts and vhost entry for `local.mmorgantextiles.com`

```
<VirtualHost *:80>
    ServerName local.mmorgantextiles.com
    DocumentRoot "/path/to/your-project-directory"
</VirtualHost>
```

- there is a grunt task configured `grunt serve` that will run an http server via node connect


## Install: **this process is only required once

```
mkdir your-project-directory && cd $_
git clone <repo location> path/to/your-project-directory
npm install
bower install
```


## Typical workflow
- edit src files in `app/` directory
- run `grunt serve` to serve and re-load the code (you can also use PHP to serve the code at local.mmorgantextiles.com)
