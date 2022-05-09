<img alt="Ignite" src="https://user-images.githubusercontent.com/17517028/167471059-c80ba610-7107-496d-a3f4-c2280983551a.png" />

<p align="center">Next Level Week #8</p>

<h3 align="center">
  NLW Return - Feedback Widget
</h3>

<p align="center">
  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

# 💻 About this project

In this version of NLW, we are going to build a widget to give feedbacks!

This is an entirely complete application, which includes the development of the server, web and mobile applications. 

## Backend

[Repo in Github](https://github.com/mbagatini/nlw-return-server)

#### How to run it?

Clone the repository to your machine.

Install the dependencies:

```bash
npm install
```

We need to save the records in the database, so in order to do it correctly, check the .env file wich contains the URL for the database connection. 

```env
DATABASE_URL="mysql://my_connection"
```

Change it to the database you want to connect. After that, is time to run the migration:

```bash
npx prisma migrate dev
```

If the configuration is ready and connected to the database, let's start the application:
```bash
npm run dev
```

## Web

[Repo in Github](https://github.com/mbagatini/nlw-return-web)

## Mobile

[Repo in Github](https://github.com/mbagatini/nlw-return-mobile)


# 🎨 Application layout

[Check on Figma](https://www.figma.com/file/p7DCgsMWVaywbGqMvo2ISF/Feedback-Widget-(Community)?node-id=100%3A2114)

![Capa](https://user-images.githubusercontent.com/17517028/167477331-beccecac-2855-4549-96ea-8fc3c992f769.png)


# Final application
