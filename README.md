yello, this is alex from the past coming to tell you what you need to do to set this thing up!
its a remix from a glitch project modified to do things more betterly and look stunning
- you wanna make sure not to screw around with funny.txt unless you wanna clear the whole database
- you need to set up the IP grabber, in views/index.html that runs from a third party site, it has an api code you need to update for the specific IP of the hosting address, you can do this by yelling at me in discord or creating a free account on the website listed in the code
- if you want to stop all incoming requests, (write, read, clear, whatever) you can set the variable DISALLOW_WRITE in the .env file to literally anything, and the whole thing will stop dead in its tracks (:

thats all for now gl

# hello-sqlite

A starter that has a database

- This app uses sqlite but you can power your apps with [a number of other storage options](https://glitch.com/storage)
- `sqlite.db` is created and put into the `.data` folder, a hidden directory whose contents aren’t copied when a project is remixed. You can see the contents of `.data` in the console under "Logs"
- To save to the database, remix this app!

On the front-end,

- Edit `views/index.html`,  `public/style.css`, and `public/client.js`
- Drag in `assets`, like images or music, to add them to your project

On the back-end,

- Your app starts at `server.js`
- Add frameworks and packages in `package.json`
- Safely store app secrets in `.env` (nobody can see this but you and people you invite)

Click `Show` in the header to see your app live. Updates to your code will instantly deploy.


## Made by [Glitch](https://glitch.com/)

\ ゜ o ゜)ノ
