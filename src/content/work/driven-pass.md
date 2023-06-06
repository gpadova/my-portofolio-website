---
title: Driven Pass
publishDate: 2023-14-03 00:00:00
img: /assets/Locker.webp
img_alt: A locker with a password with asterisks
git_hub_link: "https://github.com/gpadova/DrivenPass"
description: 
  DrivenPass is an open-source password management tool designed to help users manage their passwords securely. It allows users to store and organize their passwords in a password vault protected by a master password. The tool provides features such as automatic password generation, and the ability to securely share passwords with other users.
tags:
  - Typescript
  - Nest
  - Jest
  - Prisma
---
<h5>Short Description:</h5>
DrivenPass is an open-source password management tool that I entirely did by myself, that aims to help users manage their passwords securely. It is built using modern web technologies and follows industry-standard security practices. In this detailed explanation, we'll go over its tech stack, features, and how it provides a secure and reliable experience for its users. The project is open-source and available on versions. The first version is done in Express, and it's repo is available in this link <a href="https://github.com/gpadova/DrivenPass" target="blank">GitHub</a>. The second version was developed entirely in Nest, and it's available on this link on <a href="https://github.com/gpadova/drivenPassNest" target="blank">GitHub</a>.

<h5>Tech Stack:</h5>
DrivenPass is built using a modern tech stack that includes:

<strong>Backend:</strong> DrivenPass uses Node.js together with TypeScript, to build its backend. It uses the Express and Nest frameworks to handle requests and provide APIs to the frontend.

<strong>Database:</strong> DrivenPass stores user data in a PostgreSQL database, using the Prisma ORM, to ensure good quality ans scalabilty of its Database.

<strong>Testing:</strong> DrivenPass also includes integration testing using Jest and Supertest. By using Jest, I am able to test the interactions between different parts of the application to ensure that everything works together as intended.
Furthermore, DrivenPass boasts an impressive test coverage rate of over 90%. Test coverage refers to the percentage of code that is covered by automated tests. A high test coverage rate like this means that the DrivenPass team has put a lot of effort into ensuring that their code is thoroughly tested and works as expected.

The integration testing, combined with the high test coverage rate, is a testament to the quality of the DrivenPass codebase. It gives users confidence that the application is well-tested and reliable, and that their sensitive data is being handled securely.

<h5>Features:</h5>


<strong>Password vault:</strong> DrivenPass provides a password vault where users can store and organize their passwords. The vault is encrypted using bcrypt and crypt libraries, and is protected by a master password that only the user knows.

<strong>Automatic password generation:</strong> DrivenPass can generate strong, random passwords for users, which can help increase the security of their accounts.

<h5>Security:</h5>
DrivenPass takes security very seriously, and all of its internal requests are secured by a JSON Web Token.

<h5>Conclusion</h5>
DrivenPass is a modern password management tool that provides a secure and reliable experience for its users. Its tech stack, features, and security measures make it a great choice for anyone looking to manage their passwords securely.
