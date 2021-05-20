# Backend Coding Test

## What to do

Implement an API server that lists all public GitHub repositories of the user specified.

## Prerequisite

- Use `Go` as the programming language. Feel free to use any libraries you need.
- Write unit tests you may find helpful or important to have.
- Please spend at least 90 minutes on this test. Feel free to take more time if you wish.

## Tasks

### 1. Connect to GitHub API

Connect to GitHub API, and make repositories available for retrieval.
Feel free to choose if you are going to use the REST API or the GraphQL API.

### 2. Implement GetRepositories API

Implement `GetRepositories` API. It should take `userId` parameter, and returns repositories of the user specified.
We have prepared the schema of OpenAPI version 3 ( `api.yaml` ), so implement it according to the schema.

## Bonus Tasks

- E2E testing.
- Search the repositories (By name, owner etc)
- Change the order the repositories are shown (By stars, name, owner etc)

## Delivery

- **DON'T** fork this repository. Create a new repository in your account and send us the URL.
- Create a README file with the instructions to run the project and the tests.
