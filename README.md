# Tempcover Engineering Exercise

## Table of Contents
1. [Introduction](#introduction)
2. [Required Tooling and Setup](#required-tooling-and-setup)
3. [Test Brief](#test-brief)
4. [Spirit of the Test](#spirit-of-the-test)
5. [Running the Application](#running-the-application)

## Introduction
Welcome to the Tempcover Engineering Exercise. This test will involve using C#, React, DotNet 7.0, and AspNet Core. We have 3 main directories for you to be aware of:

- **Tempcover.Client**: This is a React app built using Vite.
- **Tempcover.API**: This is a .Net 7 Web API.
- **Tempcover.API.Tests**: This is a .Net 7 Test project.

## Required Tooling and Setup
To get started, ensure you have the following tools installed:

- **Node Version**: v18.16.1 (later versions should also work)
- **Visual Studio 2020 Community Edition** (recommended for backend work)
- **Visual Studio Code** (recommended for frontend work)

### Setup Steps
1. Fork this repository locally, which will be shared as part of the interview.
2. Ensure you have Node and .Net 7 setup.
3. Run the following command to set up your client application:
    ```sh
    cd Tempcover.Client && npm install
    ```

4. Running the the client application:
    ```sh
    cd Tempcover.Client && npm run dev
    ```
5. Running the the API from visual studio,  the application has been configured to run on localhost without HTTPS.

Once the application is running, you will see a simple react page, with brief and response from the API with Josh's cars.
   

## Test Brief
### Josh's Cars
Josh created a system that allows him to insure himself. Currently, Josh owns a Mini Cooper with a registration of A1. He has decided to get two new cars: a Ford Fiesta with a registration of A2 and a Toyota Yaris with a registration of A3. However, the system only allows one vehicle to be added.

Your task is to update the system to allow for these new additions. Please consider the following:

- Any need for new entities
- Relationships between entities
- SOLID principles
- TDD
- Frontend components
- Styling

**HINT**: You do not need to interact with a database. Feel free to edit the data returned in the file "CarOwnerRepository.cs", changing the entity structure as required.

**HINT**: We've left this pretty barebones intentionally; you are free to add additional libraries to assist with the above tasks.

**EXTRA**: If you have time, please set up a test within the `/test` project to check your work. [Playwright](https://playwright.dev/) has been set up.

## Spirit of the Test
We value interaction with us during the test over pure lines of code. We look for you to rationalize your thoughts and explain your thinking on areas you are prioritizing and areas which are deprioritizing. This approach helps us understand your problem-solving process and collaboration skills.
