# Marketing Email

This repository contains a marketing email template built using [MJML](https://mjml.io/), a framework that simplifies the creation of responsive email templates.

## Prerequisites

- **Node.js:** You need to have Node.js installed. The project has been tested with Node.js version `>=14.0.0`.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/marketing-email.git
   cd marketing-email
   ```

2. **Install the dependencies:**

   Run the following command in the project directory to install the required packages:

   ```bash
   npm install
   ```

3. **Install Nodemon (Optional):**

   Nodemon is a tool that helps develop Node.js-based applications by automatically restarting the application when file changes are detected. It is used in this project to watch for changes in the `.mjml` file and recompile it into HTML automatically.

   If Nodemon is not globally installed on your machine, you can install it using the following command:

   ```bash
   npm install -g nodemon
   ```

## Running the Project

The project uses MJML to compile the `.mjml` file into an HTML file that can be used for email campaigns.

To compile the MJML template and generate the corresponding HTML file, use the following command:

```bash
npm start
```

This command will:

- Monitor changes in the MJML file located at `src/index.mjml`.
- Automatically compile the changes and output the generated HTML to `public/index.html`.

## Folder Structure

- `src/`: Contains the MJML source file (`index.mjml`).
- `public/`: The compiled HTML output (`index.html`) will be saved here.
