# Catstronauts

👋 Welcome to the first part of our Lift-off series!

Here we begin our journey building a full-stack GraphQL example application called Catstronauts, a learning platform for adventurous cats who want to explore the universe! 😺 🚀

The first feature we'll build for the app will fetch a (mocked) list of learning tracks from a GraphQL API and display them in a card grid on our homepage.

## Preview

Here's how it'll look when we're finished:

![Catstronauts Homepage](catstronauts_homepage.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)

## Introduction

Catstronauts is a full-stack GraphQL example application that serves as a learning platform for cats who are eager to explore the universe. It allows users to browse and enroll in various learning tracks tailored to their interests and skill levels. This project serves as an introductory guide to building a full-stack GraphQL application.

In this first part of the series, we will focus on implementing the homepage feature. We will fetch a list of learning tracks from a GraphQL API and display them in a visually appealing card grid.

## Features

The Catstronauts application will eventually include the following features:

- Homepage: Display a grid of learning tracks fetched from a GraphQL API.
- Track Details: View detailed information about a specific learning track.
- User Authentication: Allow users to sign up, log in, and manage their accounts.
- Enrollment: Enable users to enroll in learning tracks and track their progress.
- Search: Provide a search functionality to find specific learning tracks.
- Admin Dashboard: Allow administrators to manage learning tracks and user data.

In this README, we will focus on the first feature, the homepage.

## Prerequisites

Before you proceed, make sure you have the following installed on your system:

- Node.js (v12 or above)
- npm (v6 or above) or Yarn (v1 or above)
- Git

## Installation

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/your-username/catstronauts.git
   ```

2. Navigate to the project directory:

   ```shell
   cd catstronauts
   ```

3. Install the dependencies:

   ```shell
   npm install
   # or
   yarn install
   ```

## Usage

To start the Catstronauts application, run the following command:

```shell
npm start
# or
yarn start
```

Open your web browser and visit `http://localhost:3000` to access the Catstronauts homepage.

## Technologies

The Catstronauts application leverages the following technologies:

- **Frontend:**
  - React: A JavaScript library for building user interfaces.
  - Apollo Client: A powerful GraphQL client for connecting the frontend with the GraphQL API.
  - CSS: Cascading Style Sheets for styling the application.

- **Backend:**
  - GraphQL: A query language for APIs that provides a flexible and efficient approach to data fetching.
  - Apollo Server: A GraphQL server that connects the frontend with the backend.
  - Node.js: A JavaScript runtime for executing server-side code.
  - MongoDB: A NoSQL database for storing and retrieving data.

## Contributing

Contributions to Catstronauts are always welcome! If you have any ideas, suggestions, or bug reports, please [create an issue](https://github