# Install SASS

Check for the node installed or not?

* Create package.json file
 `npm init -y`

* Install Dependencies
 `npm install node-sass`

* Inorder to use node SASS, create a npm script
 Inside the scrpit in package.json

```
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
},
```
> change to

```
"scripts": {
    "sass": "node-sass -w scss/ -o dist/css --recursive"
},
```

* then to run
`npm run sass`


-----

### Graphical Program called [*Koala*](!http://koala-app.com/) 
* to compile sass to css