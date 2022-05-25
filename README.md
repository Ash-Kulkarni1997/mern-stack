<h1>MERN Stack</h1>
<p>
    This project's purpose is to get acquainted with the MERN stack. In order to do so, I will be following along with <a href='youtube.com/watch?v=-0exw-9YJBo'> Traversy Media's</a> MERN series and building a goals application. This will not only include MERN stack fundamentals, but also Redux and JWT Authentication.
</p>
<hr>
<div>
    <h3>Tech Stack:</h3>
    <ul>
        <li>React</li>
        <li>Node.js</li>
        <li>Express</li>
        <li>MongoDB</li>
        <li>Mongoose</li>
    </ul>
</div>
<hr>
<div>
    <h3>Tools Used in this Project:</h3>
    <ul>
        <li>Postman</li>
        <li>MongoDB Atlas (Cloud Database) via MongoDB Compass Desktop App</li>
        <li>JWT.io</li>
    </ul>
</div>
<hr>
<div>
    <h3>Approach:</h3>
    <ol>
        <li>Create CRUD Rest APIs & Routes</li>
        <li>Set Up Cloud Database</li>
        <li>Connect to Database & Add Models</li>
    </ol>
</div>
<div>
    <h3>Setup:</h3>
    <ol>
        <li>
            Create a server.js file to be the entry point of the server.
        </li>
        <li>
            In the application root, run the following command: <b>npm init</b>
            <ol>
                <li>
                    Entry Point: server.js
                    <p>(Click "Enter" for every other question)</p>
                </li>
            </ol>
        </li>
        <li>
            Create a .gitignore file & add the node_modules folder and any .env files.
        </li>
        <li>
            Install the following npm packages as dependencies:
            <ul>
                <li>npm i express</li>
                <li>npm i dotenv</li>
                <li>npm i mongoose</li>
                <li>npm i colors</li>
                <li>npm i express-async-handler</li>
                <li>npm i bcryptjs</li>
                <li>npm i jsonwebtoken</li>
            </ul>
            <p>
                (Can also type something like the following into the terminal: 
                <br> npm i express dotenv mongoose colors
            </p>
        </li>
        <li>
            Install the following npm packages as DEV dependencies:
            <ul>
                <li>npm i -D nodemon</li>
                <p>
                    (This package constantly watches our server.js files so there is no need to constantly restart it.)
                </p>
            </ul>
        </li>
        <li>
            Add the following scripts to package.json:
            <ul>
                <li>"start": "node backend/server.js"</li>
                <li>"server": "nodemon backend/server.js"</li>
            </ul>
        </li>
    </ol>
</div>


