# todo-app
This is a todo app built from ground up with React.js, Webpack and Babel.

## In the context of Babel
Babel is a transpiler which is best known for allowing codes written in ES6 to run in browsers which do not support ES6 at the moment.
- A **preset** is just a set of plugins used to support a language feature.
- The __react preset__ adds support for JSX
- **env preset** on the other hand, apart from compiling down to a minimum of ES5

## Webpack
Webpack is a module bundler and a task runner.
- ```context``` simply tells Webpack to always run from the root directory of your project, Also ```__dirname``` is just a NodeJS global variable which refers to the root directory of your project.
- The ```entry``` property simply tells Webpack about the entry point of your app. 
- ```cheap-eval-source-map``` simply tells Webpack to add all your source-maps into your bundled code.
- The ```output``` object has two properties: ```path```and ```filename```. ```path``` is just the path for our bundled file which is called ```bundle.js``` in this case. You can call the ```filename``` whatever you want.
- The ```resolve.extensions``` property simply tells Webpack the order in which it should look for a particular file.
- ```Module``` is an array of rules that Webpack is going to use to apply different loaders to your code.
