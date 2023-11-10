# Question-bank-fe

QBG (Question Bank Generator) is a system which has a multitude of structured questions and answers on a range of topics for the classes/batches. These questions and answers can be used to auto-generate (database-driven) template based SEO landing pages. SEO is an important user acquisition channel and implementation of the database driven SEO landing pages will boost the SEO traffic to our website. With proper schema markup implementation, these Q&As also show up as a "Questions and answers" featured snippet on SERP. 

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Prerequisites](#prerequisites)
4. [Getting Started](#getting-started)
5. [Usage](#usage)
6. [Testing](#testing)
7. [Deployments](#deployments)
8. [Contributing](#contributing)
8. [Contributors List](#contributors-list)
9. [License](#license)

## Introduction <a name="introduction"></a>

Briefly introduce the project here.
QBG (Question Bank Generator) is a system which has a multitude of structured questions and answers on a range of topics for the classes/batches. These questions and answers can be used to auto-generate (database-driven) template based SEO landing pages. SEO is an important user acquisition channel and implementation of the database driven SEO landing pages will boost the SEO traffic to our website. With proper schema markup implementation, these Q&As also show up as a "Questions and answers" featured snippet on SERP. 

## Project Overview <a name="project-overview"></a>

- **Purpose**: Explain the project's purpose.
The objective is:
Students should be able to find PW Q&A page while searching for questions on Google - Acquisition through search engine
Students should be able to navigate to the Q&A page while searching for questions directly on PW web - ease of usage for PW's captive   audience (increase adoption of Q&A section)
Image and text search both should be supported on PW - Ask doubt capability of Saarthi - To be enabled on website as well
Students are able to utilise QBG for practising topic-wise problems with filters and sort options like difficulty level, popularity, previous year questions - QBG categorisation to be enhanced as well 
Identify the next action(s) we want the user to take

- **Features**: List key features.
Students will search questions without login . 
They can upload images of questions and get response 

- **Architecture**: Describe the technology stack and project structure.
Will be using NextJs to create all components

Shared Components yet to be decided to use npm package or submodules

SSR or SSG pages will be decided based on stress test on NextJs

Unit test will be incorporated using Jest and react testing library

Typescript will be used with proper type check

Linting will be done (next lint / other industry standard linting)

Pre commit hooks will be incorporated – Husky

Will Dockerise 

Creation of CI/CD pipeline in gitlab for linting and test case coverage

Will use third party carousel for slider

- you can check architecture here -> https://physicswallah001.atlassian.net/wiki/spaces/EN/pages/edit-v2/205357073

## Prerequisites <a name="prerequisites"></a>

Nextjs
Tailwind css
jest testing library
use Dockerise
Husky for pre-commits
- ...

## Getting Started <a name="getting-started"></a>

- Installation: Instructions for setting up the project.
npm run dev
- Configuration: Configuration files or environment variables.
.env
- Initialization: Database setup, migrations, or seeding.
...


## Usage <a name="usage"></a>

- Examples: Code examples or usage scenarios.

- API Documentation: Link to or embed API documentation.

- Screenshots: Include visuals to help users understand.


## Testing <a name="testing"></a>

- **Test Scenarios**: List various test scenarios and use cases that the testing team should cover.
- **Test Data**: Specify any sample data or inputs that are necessary for testing.
- **Test Automation**: If applicable, provide guidance on running automated tests and tools used.
- **Bug Reporting**: Explain how to report bugs, including the format for bug reports and where to submit them.
- **Testing Environment Setup**: If there are specific testing environment requirements, outline how to set them up.

## Deployments <a name="deployments"></a>

In the **Deployments** section, you should provide information related to deploying the project to different environments. Include the following:

| Environments   | Environment URLs             | Jenkins Jobs       | Deployment Instructions                                     |
|----------------|------------------------------|--------------------|-------------------------------------------------------------|
| Development    | ---                                  | -----       | 1. Check out the code from the development branch.         |
|                |                              |                    | 2. Run unit tests to ensure code quality.                  |
|                |                              |                    | 3. Build the application.                                 |
|                |                              |                    | 4. Deploy to the development server.                       |
| Staging        | https://pw-qbg-stage.penpencil.co/question-answer/  | https://jenkins.penpencil.co/job/Staging/job/pw-qbg/   | 1. Merge code into the staging branch.                    |
|                |                              |                    | 2. Run integration tests on the staging server.            |
|                |                              |                    | 3. Build the application with staging configurations.      |
|                |                              |                    | 4. Deploy to the staging server.                           |
| Production     | https://www.pw.live/question-answer      | https://jenkins.penpencil.co/job/Production/job/pw-qbg/ | 1. Ensure a proper code merge. Merging code into the development branch will automatically trigger deployment to the development environment.                  |
|                |                              |                    | 2. After merging the code, please perform a sanity check.    |



## Contributing <a name="contributing"></a>

- Guidelines: How to contribute (code style, issue reporting, pull requests).
- Code of Conduct: Link to the organization's code of conduct.

### Contributors List <a name="contributors-list"></a>

We'd like to thank the following contributors for their valuable contributions to this project:

- Vicky Paul 
- Amandeep Singh 
- Aditya Kumari
- Rupali Bharti

Thank you for your support and contributions!

## License <a name="license"></a>

This project is licensed under the [License Name](link-to-license).