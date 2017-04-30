# learn-sass
READMEs and code snippets for learning SASS


## Setting up SASS

1. Initialise npm
1. Install SASS
    ```bash
    npm install node-sass
    ```
1. Edit package.json and add this script:
  ```json
  "sass": "./node_modules/.bin/node-sass --source-map true public/_sass/main.scss public/assets/css/main.css"
  ```
  where `public/_sass/main.scss` is the input SASS file and `public/assets/css/main.css` is the output CSS file, which will be bundled with the source map too.
