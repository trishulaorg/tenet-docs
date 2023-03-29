---
sidebar_position: 1
---

# Technology Overview

To let you know how tenet works, we will explain the technologies used in tenet.

Tenet is a highly-scalable, community driven OSS social media platform. It is built on top of the following technologies:

## Frontend

All dependencies below are automatically installed when you run `npm install` in the root directory.

- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/) for type safety
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [heroicons](https://heroicons.com/) for icons


## Backend

The backend of tenet is written in Rust. It is a highly performant language that is also memory safe. It is also a statically typed language, which means that it is very easy to debug.

The backend is maintained on the other repository, [tenet-api-server](https://github.com/trishulaorg/tenet-api-server).

To run the backend, you might need to install the following dependencies:

- [Rust](https://www.rust-lang.org/)
- [MySQL](https://www.mysql.com/)
- [Redis](https://redis.io/)

It also provided as a docker image. To run the backend, you might need to install the following dependencies:

- [Docker](https://www.docker.com/)
- [Docker compose](https://docs.docker.com/compose/)

Use `docker compose up` to run the backend