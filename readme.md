# Mini Dev Static Server

Just a small server for doing dev work when you need to serve some static assets really quickly.

## install/usage

Drop the server.js file into your project folder and run `node server.js`. The server will automatically try to find a `index.html` to serve, but you can also specify specific files in a URL.

Alternatively, you can drop the file in your home directory, and run `node ~/server.js --relative-root` or `node ~/server.js -r` from anywhere, and it will use the current working directory as the root directory for serving files. Even easier, you can alias something in your `.bash_profile` to run this quickly, like `alias srv="node ~/server.js -r"`.

## tl;dr

1. put `server.js` in your home `~` directory
1. add `alias srv="node ~/server.js -r"` to your `.bash_profile`
1. `cd` into your project directory
1. `srv` in terminal, pull up `localhost:3000` in your browser
