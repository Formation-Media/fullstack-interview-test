# Nested Menu Coding Test

## Overview
You are tasked with building an application that consumes a nested menu JSON from the following URL:
[https://formation-media.github.io/fullstack-interview-test/menu.json](https://formation-media.github.io/fullstack-interview-test/menu.json)

The app should have two pages with navigation between the pages:

### Display Page
- Show the nested menu structure as a tree view or any nested layout
- Bonus points for clean, user-friendly styling

### Edit Page
- Allow renaming any menu item
- Allow moving a menu item to a different place in the tree
- Allow deleting any menu item
- Changes should persist in a non-volatile serverside storage (eg a database)

## Requirements
- You must fetch the JSON data dynamically from the provided URL (do not hardcode the menu JSON)
- Use any modern JavaScript frontend framework such as React, Next.js, Svelte, Vue, Angular, or Remix

### Backend (optional, extra credit):
- Implement a backend with SQLite or any lightweight DB to persist the menu and handle edits

### Containerization (recommended):
- Provide a Docker container setup to build and run your app (frontend, backend, or both)
- Include a Dockerfile
- Optionally, a docker-compose.yml if multiple services exist
- Include instructions on how to build and run the container(s)
- Provide clear setup and run instructions in your README

## README Requirement
As part of your submission, please include a comprehensive README file that covers the following:

- Project overview: A brief description of your solution and approach
- Setup instructions: How to install dependencies, build, and run the application locally if applicable
- Backend (if implemented): How the backend is structured and how to run it
- Bonus features: Highlight any extra work you did beyond the base requirements

A clear, well-structured README and comments in the code will help us understand your thought process and makes it easy for us to test your solution.
