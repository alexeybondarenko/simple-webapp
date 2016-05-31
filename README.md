# Simple Webapp

Boilerplate for simple web application. 

- Gulp
- s18n 
- SASS with Compass
- Jade
- Angular JS annotation
- Production build ready
- JS config generator from json file
- Support `.env` file


## Usage

Clone boilerplate

```sh
git clone --depth=1 --branch=master https://github.com/alexeybondarenko/simple-webapp.git ./projectName
cd projectName
rm -rf !$/.git
```

Update `gulpfile.js`. Change prefix in deploy-prefix task to the `repositoryName`.

## Tasks

`build` - build project files

`default`- build, serve server and watch changes

`clean` - clean 

`deploy` - deploy to the ghPages

## Parameters

`production` - include production tasks

`env` - specify enviroment. Using in config generating.

Support specifying parameters in `.env` file.

```
production=true
env=sandbox
```

task `gulp build` will run as `gulp build --production --env sandbox`
