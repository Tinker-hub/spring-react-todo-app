# Spring Boot and React To-Do App

### Summary
This is yet another to-do app. Like the other _-probably-_ millions of similar to-do apps on the Internet, this app can be used for keeping track of your tasks.
Allows you to create tasks on its simple and clean interface. You can also mark the tasks as completed or delete them.
This was a Spring Boot starter project for me.

### Technologies
- JDK 17
- Spring Boot with Maven
- PostgreSQL
- React
- TypeScript

### Running

##### Backend

```shell
mvn spring-boot:run
```

##### Frontend

You need to fill the required fields for configuring the backend connection.
You can leave the `VITE_API_URL` field as it is, if you are running the backend on the same machine.
After that, you can run the frontend with the following commands:

```shell
bun install
bun run dev
```

> `bun` is used during the development of this app but the commands above can be replaced with `npm`, `yarn` or `pnpm`.


It will build the frontend app and run the backend and frontend services with a PostgreSQL database.
