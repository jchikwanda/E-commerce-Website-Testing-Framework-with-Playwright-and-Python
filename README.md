# E-commerce Website Testing Framework with Playwright and Node.js

This is a project that demonstrates how to use Playwright with Node.js to create an automated testing framework for an e-commerce website. The framework can be used to test various aspects of the website, such as searching for products, adding them to the shopping cart, and making a purchase.

## Project Structure

The project is organized into three directories:

- `client/`: A directory containing a React frontend that allows users to interact with the e-commerce website. The frontend provides a search form, a shopping cart, and a checkout page.
- `server/`: A directory containing an Express server that provides an API for interacting with the e-commerce website. The server is responsible for handling user authentication, product searches, and checkout transactions.
- `README.md`: The README file for the project.
- `requirements.txt`: A file containing a list of Python dependencies required by the project.

## Getting Started

To get started with the project, you will need to have the following installed on your system:

- Node.js and npm
- Python 3.7 or later
- Playwright

You can install the necessary dependencies by running the following commands in the project root directory:

```
npm install
pip install -r requirements.txt
```


Once you have installed the dependencies, you can start the server and client by running the following commands:

```
npm run start:server
npm run start:client
```


This will start the server and client on separate ports. You can then run the tests by running the following command:

```
python main.py
```

This test logs in as a user, searches for a product with the name "product name", adds it to the shopping cart, and verifies that the shopping cart contains one item.
Contributing

If you would like to contribute to the project, please open a pull request on GitHub. We welcome contributions of all kinds, including bug fixes, new features, and documentation improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Acknowledgments

This project was inspired by the Playwright documentation and examples, as well as the many open-source contributors who have helped to make Playwright such a useful tool for web automation.
