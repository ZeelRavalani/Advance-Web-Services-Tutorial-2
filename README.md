# Tutorial 2

This repository contains the code for Tutorial 2, demonstrating the deployment of a simple React application on Netlify.

* *Date Created*: 30 May 2024
* *Last Modification Date*: 30 May 2024
* *Lab URL*: <https://subtle-toffee-5f1d35.netlify.app/>
* *GitHub URL*: <https://github.com/ZeelRavalani/Advance-Web-Services-Tutorial-2>
* *GitLab Tutorial 2 URL*: <https://git.cs.dal.ca/ravalani/csci-5709-tutorials/-/tree/main/Tutorial2?ref_type=heads>
* *GitLab Individual Tutorial 2 Repo URL*: <https://git.cs.dal.ca/ravalani/csci-5709-tutorial2/-/tree/main>
* *GitLab Assignment URL*: <https://git.cs.dal.ca/ravalani/csci-5709-assignments/-/tree/main>
* *GitLab Group Project URL*: <https://git.cs.dal.ca/kottur/csci-5709-group-12/-/tree/main>
    * *GitLab Group Project **zeel-ravalani** Branch URL*: <https://git.cs.dal.ca/kottur/csci-5709-group-12/-/tree/zeel-ravalani?ref_type=heads>
    * *GitLab Group Project **pratik-sakaria** Branch URL*: <https://git.cs.dal.ca/kottur/csci-5709-group-12/-/tree/pratik-sakaria?ref_type=heads>
    * *GitLab Group Project **namrata-bhaumik** Branch URL*: <https://git.cs.dal.ca/kottur/csci-5709-group-12/-/tree/namrata-bhaumik?ref_type=heads>
    * *GitLab Group Project **sanjana-rampurkottur** Branch URL*: <https://git.cs.dal.ca/kottur/csci-5709-group-12/-/tree/sanjana-rampurkottur?ref_type=heads>
    * *GitLab Group Project **prithvi-manoj-krishna** Branch URL*: <https://git.cs.dal.ca/kottur/csci-5709-group-12/-/tree/prithvi-manoj-krishna?ref_type=heads>
    * *GitLab Group Project **mdsamshad-rahman** Branch URL*: <https://git.cs.dal.ca/kottur/csci-5709-group-12/-/tree/mdsamshad-rahman?ref_type=heads>

## Authors

* [Zeel Ravalani](zeel.ravalani@dal.ca) - *(Developer)*

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development, testing, and deployment purposes.

### Prerequisites

To run this project locally, you will need to have the following software installed:

* Node.js (https://nodejs.org/)
* npm (comes with Node.js) or yarn (https://yarnpkg.com/)

### Installing

Follow these steps to set up the development environment:

1. Clone the repository:

    ```bash
    git clone https://github.com/ZeelRavalani/Advance-Web-Services-Tutorial-2.git
    cd Advance-Web-Services-Tutorial-2
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

    or if you prefer yarn:

    ```bash
    yarn install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

    or with yarn:

    ```bash
    yarn start
    ```

You should see the application running at `http://localhost:3000` with a message "It Works!".

## Running the tests

No automated tests have been implemented for this tutorial.

## Deployment

To deploy the project on a live system, follow these steps:

1. Build the project:

    ```bash
    npm run build
    ```

    or with yarn:

    ```bash
    yarn build
    ```

2. Deploy the contents of the `build` directory to your hosting service. For this tutorial, we will use Netlify.

3. Connect your GitHub repository to Netlify and follow the instructions to deploy the site. Ensure the build command is `npm run build` and the publish directory is `build`.

## Built With

* [React](https://reactjs.org/) - The web framework used
* [Create React App](https://create-react-app.dev/) - Boilerplate code used to set up the React project

## Sources Used

No external code sources were used for this tutorial.

## Artificial Intelligence Tools Used

No AI tools were used for this tutorial.

## Acknowledgments

* Hat tip to the developers of Create React App for providing an easy way to bootstrap React projects.
* Inspiration for the deployment process from [Netlify documentation](https://docs.netlify.com/).

