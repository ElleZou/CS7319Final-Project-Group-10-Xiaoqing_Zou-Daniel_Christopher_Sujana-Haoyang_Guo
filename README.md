# CS7319 Intelligent Student Academic Management System(Pub/Sub Learning Management System PSLMS)



## Team members:
Xiaoqing Zou , Daniel Christopher Sujana, Haoyang Guo

## Presentation Video
[Youtube](https://www.youtube.com/watch?v=oG6RNOUYs-Y)

## Selected Implementation Usage



### Install JDK 21

Will need to install GraalVM version or just the plain JDK 21 if not interested in native images

### Unzip the project
Unzip and run `mvnw clean package` to ensure the project compiles

### Import into your IDE
IntelliJ or VS Code will both work. Lets also cleanup some stuff that will slow us down in this demo.

- Cleanup the `src/test/java`
- Remove the testing dependencies
- Set the version of app to `1.0`
- Execute maven install in the IDE under maven

### Run the app - Lots of choices

Spring Boot makes it really easy to run your app during development and there are lots of packaging options for running in production.

#### Through the IDE

Using the play button from the main class - the tomcat application will run on 8080 port.

#### Using Maven

```
./mvnw clean spring-boot:run
```
Once the application starts, use the following endpoints to access the respective portals:

Professor - http://localhost:8080/professor.html
Student - http://localhost:8080/student.html

Make sure the application is connected to the SQL database and execute the DDL and insert scripts.


## Unselected Implementation Usage

### Development Description
Plantform: Windows 11

IDE: VSCode

Framework: Node.js(https://nodejs.org/en/download), React, Next.js, Mui.js,Faye.

### Requriemnt 

`npm install next@latest react@latest react-dom@latest`

`npm install @mui/material @emotion/react @emotion/styled`

`npm install @mui/icons-material`

`npm install faye`

run the project `npm run dev`

run the pub/sub connection `node pubsub.js`

### user example:
"email": "jdoe@smu.edu",student
"email": "rsharp@smu.edu", teacher for 7314
"email": "rsam@smu.edu",student

### Next.js readme Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```



Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

#### Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

#### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
