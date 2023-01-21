# Dating App

![ASP.NET Core](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

![Deploy status](https://github.com/kebha/da/actions/workflows/docker-push.yml/badge.svg)

This is a mock up dating web app built using ASP.NET Core and Angular. Users are able to upload details/pictures about themselves, they may also view other member's profile to "like" or live chat with them.

## Demo

**[Link to Application](https://da-dating-app.fly.dev/)**

Login (to skip registration):

- username: lisa
- password: Pa$$w0rd

## Implementations

### back-end

- secure login functionality using ASP.NET Core Identity
- JSON Web Token authentication
- Online presence and Live chat using SignalR
- Repository & Unit of Work design pattern
- continuous deployment pipeline using GitHub Actions

### front-end

- reduced API calls and loading times through caching data and pagination
