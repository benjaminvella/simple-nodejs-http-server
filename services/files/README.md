# Front part of the PS8 project

This folder should contain all the static files that could be returned by the file server to clients.

By default, the HTTP server used in `services/files/logic.js` will start checking for files inside this repo.
This means that when a client targets `projectName.ps8.academy/folder1/file1.png`*, 
the HTTP server will try to find `file1.png` inside `front/folder1`.

You are free to change this behavior, and to manage the folders and files inside this project however you like, 
but remember to update the `services/files/logic.js` file accordingly.

*Note: At the start of the project, you don't have a `ps8.academy` URL, so you will have to use localhost.