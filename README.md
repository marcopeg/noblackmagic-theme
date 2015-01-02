noBlackMagic.com Theme
======================

This theme uses PoliteJS' [_Workspace_][wks].

> In order to run the follwing Quick Start scripts you need 
> [NodeJS][node] and [NPM][npm] up and running on your computer.
> You also need [GulpJS][gulp] installed globally.

    // install Gulp (if you don't have it yet)
    npm install -g gulp
    
    // quick project startup
    npm install && gulp
    
## Folder Structure

    /project-root
      /app                  theme source files
      /build                compiled web theme 
      /node_modules         dependencies packages
      - workspace.conf.js
      - webpack.config.js
      - karma.conf.js
      - Gulpfile.js


[wks]: https://github.com/PoliteJS/workspace "Single Page Application Workspace"
[npm]: npmjs.org
[node]: nodejs.org
[gulp]: gulpjs.com
[wpak]: http://webpack.github.io/
[less]: lesscss.org