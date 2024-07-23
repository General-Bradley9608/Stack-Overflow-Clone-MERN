https://user-images.githubusercontent.com/43780137/158059050-481ffa30-e415-4156-aea7-072c817f2ae2.mp4

### [🌐 Website](https://stackoverflow-clone-client.vercel.app)

### API Hosted On
- __[stackoverflow-clone-api.onrender.com](https://stackoverflow-clone-api.onrender.com) (Primary)__
- __[stackoverflow-clone-backend.herokuapp.com](https://stackoverflow-clone-backend.herokuapp.com)__

As the name suggests, this project is a clone of a famous Q/A website for professional and enthusiast programmers built solely by me using a completely different stack.

This repo consists of the Frontend code of the project, the backend code is in __[Stackoverflow-Clone-Backend](https://github.com/General-Bradley9608/Stack-Overflow-Clone-Backend)__

## My Tech Stack (MERN)

#### Front-end

- Front-end Framework: `React.js (with Redux)`
- Styling: `SASS` and `BOOTSTRAP`

#### Back-end

- For handling index requests: `Node.js with Express.js Framework`
- As Database: `MySQL with Sequelize`
- API tested using: `POSTMAN`

## Guidelines to setup

There are two ways to setup the project: manually or using the Dockerfile. Read below for more details:

### Manual Setup

1. Open your local CLI -

   ```
   mkdir Stack-Overflow-Clone-MERN
   cd Stack-Overflow-Clone-MERN
   ```

2. Setup the backend code -
   
   __NOTE:__ For Frontend Developers, if they dont want to setup the Backend Code, they can skip the Step 2, and make sure they follow the optional step mentioned in Step 4

   - Create a `.env` file and the format should be as given in `.env.example`.
   - Clone the code & install the modules-

     ```
     git clone https://github.com/General-Bradley9608/Stack-Overflow-Clone-Backend.git
     cd Stack-Overflow-Clone-Backend

     npm install
     ```

   - Open your MySQL Client -

     ```
     CREATE DATABASE stack_overflow;
     ```
     NOTE: Don't forget to keep the database name same in the `.env` and here.

   - Run the index `npm start`.

3. Open a new CLI terminal and goto the root `Stack-Overflow-Clone-MERN` folder you created in the first step.
4. Setup the Frontend code -

   - Clone the code & install the modules-

     ```
     git clone https://github.com/General-Bradley9606/Stack-Overflow-Clone-MERN.git
     cd Stack-Overflow-Clone-MERN

     npm install
     ```

   - Run the client index `npm start`.

Let me know if you are interested and would want me to assign it to you

### Docker Setup

The back-end has support for Docker. So if you want to run the back-end in a container, you need do:

- Setup environment variables in `.env` file. Note when you use Docker setup and run the database in localhost (host machine), you need to setup the environment variables for use correct IP of MySQL Database. Please, read [here](https://docs.docker.com/compose/environment-variables/) and [here](https://docs.docker.com/desktop/windows/networking/) for more details.

- Build the Docker image:
  ```
  docker build -t stackoverflowclone .
  ```
- Run the container. For example, if you want to run the container in a new terminal, you can do:
  ```
  docker run -d -p 5000:5000 stackoverflowclone
  ```

The default port of api is 5000. After running the container, you can access the api by typing:

    http://localhost:5000/api/<endpoint that you request - see next section>

_Follow the steps properly (manual or Docker) and you are good to go._

## Contributing

- Go to `Contributing.md`

_Video Last Updated on 7th March, 2022_

#### IMAGES

<img src="/demo/images/1.png" width=340px /><img src="/demo/images/2.png" width=340px />
<img src="/demo/images/3.png" width=340px /><img src="/demo/images/4.png" width=340px />
<img src="/demo/images/5.png" width=340px /><img src="/demo/images/6.png" width=340px />
<img src="/demo/images/7.png" width=340px /><img src="/demo/images/8.png" width=340px />
<img src="/demo/images/9.png" width=340px /><img src="/demo/images/10.png" width=340px />
<img src="/demo/images/11.png" width=340px /><img src="/demo/images/12.png" width=340px />
