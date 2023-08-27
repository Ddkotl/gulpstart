# gulpstart

app (dir for work);
dist (dir for cleane files);
gulpfile.js (settings gulp);
package.json (list of all plagins);

console comands:

    before work:
        npm install --global gulp-cli (install gulp)
        npm i (instull plagins)

    for work:
        gulp (for work mains plagins)
        gulp build (for copy in dir dist usefull files)

bugs fix:
    1. 
        -go to node_modules/gulp-fonter/dist/index.js
        -in the string:   
        newFont.path = source.dirname + '\\' + source.stem + '.' + type;
        change \\ on /
