# Globals - No Window -> Because there's no browser

1. __dirname - path to current directory
2. __filename - file name
3. require - function to use modules (CommonJS)
4. module - info about current module (file)
5. process (very useful) - info about env where the program in being executed
    - when it comes to a node app, when you deploy for example your api so for example your server, where it's sitting? it is sitting on digital ocean or heroku? of course it's already a different environment and of course based on that environment you can make a bunch of decisions in your application.

console.log(__dirname)

# Modules

1. CommonJS, every file in node is module (by default)
2. Modules - Encapsulated Code (only share minimum)

# HTTP 

1. 