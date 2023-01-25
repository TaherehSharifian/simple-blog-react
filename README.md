# Simple Blog

This is a small and simple project made with React.js


## more about Simple Blog

This blog contains a few blog posts which you can **add** to with `new Blog` button.
Also, you can easily **delete** a post by clicking the `delete` button at the end of each post.
Multiple routes are built in the blog as follows:

 - `/` which is the home route, where all blog posts are available
 - `/create` which you can create a new blog post
 - `/blogs/${id}` which loads a post with a unique id
 
 Simple Blog also has a **custom hook** to fetch data from a local json-server.

## how to start the project

> you must have `Node.js` installed on your machine.
 1. clone the repository to your local machine,
 2. `cd` to the project folder in any terminal (cmd or vscode integrated terminal),
 3. run `npm init` for node package module initiation,
 4. run `npm install` to install all the dependencies required for this project. A list of all dependencies is available in the *package.json* file
 5. in one terminal, run `npx json-server --watch data/db.json --port 8000` to start the local json-server for feting and creating new data to the local database
 > The local database in located in `data/db.json`. so if you changed this folder in anyway make sure to call the proper file. Also, React.js default port number is `3000` that is why you need to have a new port number for json-server. `8000` in used in the project. if you called another port, make sure to make changes in the code files where this port in used to fetch data from json-server local database
 6. **in another terminal**, run `npm run start` to start the project. this will automatically opens the project in your default browser.
 7. get innovated and explore this project :)
