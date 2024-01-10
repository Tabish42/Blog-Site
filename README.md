
# Daily Journal Web Application

This web application allows users to create and publish blog posts, view an about page, and contact the site administrators. The application is built using **Node.js**, **Express.js**, **MongoDB**, and **Bootstrap 5** for styling.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Home Page**: Displays a list of existing blog posts and a button to compose new posts.
- **Compose Page**: Allows users to create new blog posts by providing a title and content.
- **About Page**: Provides information about the site.
- **Contact Page**: Displays contact information for the site administrators.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/daily-journal.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up MongoDB:
   - Ensure MongoDB is installed and running on your system.
   - Configure the MongoDB connection URL in `app.js`:

   ```javascript
   mongoose.connect("mongodb://localhost:27017/blogDB");
   ```

## Usage

1. Start the server:
   ```bash
   node app.js
   ```
2. Access the application in your browser at `http://localhost:3000`.

## Dependencies

- **Express**: Web application framework for Node.js.
- **EJS**: Templating engine for rendering dynamic web pages.
- **Mongoose**: MongoDB object modeling for Node.js.
- **Bootstrap**: CSS framework for styling.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
