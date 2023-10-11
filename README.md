# :ping_pong: Project Overview

This project is a full stack web app allowing a user to register, connect with friends, talk to friends and play with friends.
It is a React-NodeJs-Postges stack application

### How to use
- In a terminal, type in *docker-compose up --build*
- **Requirements** : a .env file that I'll provide if you contact me, for more info see end of this document
- Open Chrome or Firefox and type in *http://localhost:3000*

### A Few Screenshots

![Screenshot from 2023-10-11 09-30-25](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/13d12aef-3eff-4686-aeb3-f030251fc9b4)
![Screenshot from 2023-10-11 09-33-13](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/7502465f-fc71-4170-bde6-2281f196dce9)
![Screenshot from 2023-10-11 09-33-46](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/0817cd1e-2bbd-4beb-adfd-1a0dd5bd36dd)
![Screenshot from 2023-10-11 09-34-01](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/852cbacd-3759-4be8-87bc-1f7bb0314764)
![Screenshot from 2023-10-11 09-34-24](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/e88f2d35-120f-494f-9710-e6aa9b3762ca)
![Screenshot from 2023-10-11 09-35-21](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/b345cea9-34d8-40a8-a804-505526d344a5)
![Screenshot from 2023-10-11 09-35-54](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/94396964-6eb5-468d-a4da-f195bb72ca0a)
![Screenshot from 2023-10-11 09-36-00](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/93c62752-2996-4406-bb12-c386f911af76)
![Screenshot from 2023-10-11 09-36-19](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/391a7ee2-9d63-493f-a010-7e824369a93a)
![Screenshot from 2023-10-11 09-36-39](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/7fc2cd8b-79cf-46bc-bf93-ecf381985a8d)
![Screenshot from 2023-10-11 09-37-05](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/3d9dda11-62b3-412f-ba2d-00c1a5c5fb98)
![Screenshot from 2023-10-11 09-37-11](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/33fae252-e61b-4096-a6a9-59472ff2fc28)
![Screenshot from 2023-10-11 09-37-16](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/6cc41452-ac71-40f7-a1cf-db13519c3e02)
![Screenshot from 2023-10-11 09-37-20](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/b0270307-21dd-45bf-acf1-76331670b324)
![Screenshot from 2023-10-11 09-37-51](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/c538ff5b-0661-4b66-a278-f2bfa7a512f4)
![Screenshot from 2023-10-11 09-38-07](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/48337fe6-24ca-41b8-93f1-f51fa4e56c7b)
![Screenshot from 2023-10-11 09-38-33](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/8ed15296-37ba-4d40-8d3c-4c317d020682)
![Screenshot from 2023-10-11 09-38-55](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/acd2bcb8-c310-46dc-ae2f-b7a8ba5acb55)
![Screenshot from 2023-10-11 09-39-01](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/cd3be85d-0183-4258-bc36-96fe24fbbd7a)
![Screenshot from 2023-10-11 09-39-06](https://github.com/Alicia-bites/ft_transcendance/assets/51951741/afb52992-0655-4097-8f2b-507574b571b9)

### :adult: Registration and Updates interface

- Implementation of OAuth to connect with 42 API
- Implementation of form registration with unique nickname and password and an avatar
- Implementation of two factor authentication with google Authenticator
- Implementation of user information's updates (nickname, password and avatar)
- Implementation of user status updates


### :speech_balloon: Chat interface

- Implementation of real-time communication between user(s)
- Creation of public, private, public with password channels
- Creation of private conversation between two users
- Access to user profile from conversation
- Access to game interface from chat interface
- Implementation of blocking users feature
- Implementation of roles and hierarchy :
    - The owner of a channel is on top of the hierarchy and has the rights to ban/mute/kick others members and admins (He is automatically an admin)
    - The admins of a channel can ban/mute/kick other members but not other admins or the owner
    - The members can only join channels or leave it 


### :ping_pong: Game interface

- Implementation of a live pong 
- Implementation of a matchmaking system - the users can join a queue until they get automatically matched with someone else.
- Implementation of the customisation Options (eg. Power-ups, Different Maps), however, the user should be able to select a default version of the game.
- Implementation of the responsivity for the game


### :technologist:  Friends interface

- Implementation of friends requests
- Implementation of friends acceptance
- Implementation of friends suggestions

### :desktop_computer: User profile interface & Leaderboard

- Access to user profile match history
- Access to user profile statistics
- Access to the leaderboard
- Access to the user profile and informations (status, name ...)


<br>
<br>


# :keyboard: Development

<img alt="React" src="https://img.shields.io/badge/React-20232a.svg?logo=react&logoColor=%2361DAFB"> <img alt="Nest" src="https://img.shields.io/badge/nestjs-%23E0234E.svg?logo=nestjs&logoColor=white"> <img alt="Docker" src="https://img.shields.io/badge/docker-%230db7ed.svg?logo=docker&logoColor=white"> <img alt="PostgreSQL" src ="https://img.shields.io/badge/PostgreSQL-316192.svg?logo=postgresql&logoColor=white"> <img alt="Prisma" src="https://img.shields.io/badge/Prisma-3982CE?logo=Prisma&logoColor=white"> <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white"/>

### :runner: To run th project 
```
For the Authentication with 42 and the connection with the database, a ".env" is needeed with the secret variables
Contact us to get it and run the project with :  docker-compose up --build
```
- project built with my two wonderful teammates Amina (https://github.com/ELKAMINA) & Anthony (https://github.com/BarrierAntho)

