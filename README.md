# Hodlinfo-clone-main

This is a clone of the Hodlinfo website (https://www.hodlinfo.com/) built using Node.js, Express.js, PostgreSQL, EJS, and other web technologies.

## Description

Hodlinfo-clone-main is a web application that fetches data from the WazirX API (https://api.wazirx.com/) to display cryptocurrency ticker information. It allows users to view the latest prices, buy and sell rates, trading volumes, and base units of the top 10 cryptocurrencies. The application uses a PostgreSQL database to store and retrieve the cryptocurrency data, and it is built using the Express.js framework for the backend, EJS for the templating engine, and other web technologies for the frontend.

## Features

- Fetches cryptocurrency data from the WazirX API
- Stores and retrieves cryptocurrency data in a PostgreSQL database
- Displays cryptocurrency ticker information in a user-friendly format
- Supports basic CRUD (Create, Read, Update, Delete) operations for cryptocurrency data
- Utilizes EJS templating engine for dynamic rendering of views
- Handles error cases and displays appropriate error messages
- Provides a simple and intuitive user interface

## Installation

To run the Hodlinfo-clone-main application locally, follow these steps:

1. Clone the GitHub repository: `git clone https://github.com/Selva-2309/Hodlinfo-clone-main.git`
2. Install the dependencies: `npm install`
3. Set up a PostgreSQL database and update the database configuration in `config/db.js` with your own credentials.
4. Start the application: `node app.js`
5. Access the application in your web browser at `http://localhost:{PORT}` (replace `{PORT}` with the port number specified in `app.js`)

Note: Make sure to have Node.js and PostgreSQL installed on your system before running the application.

## Usage

- Open your web browser and access the application at `http://localhost:{PORT}`.
- You will be able to view the latest cryptocurrency ticker information on the homepage.
- You can also perform CRUD operations by clicking on the buttons provided for each cryptocurrency.
- To add a new cryptocurrency, click on the "Add New" button and fill in the required details in the form.
- To edit an existing cryptocurrency, click on the "Edit" button and update the details in the form.
- To delete a cryptocurrency, click on the "Delete" button.

## Contributing

Contributions to Hodlinfo-clone-main are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. Contributions should be made in accordance with the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md).

## License

Hodlinfo-clone-main is open-source software released under the [MIT License](LICENSE).



