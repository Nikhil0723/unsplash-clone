# Unsplash Clone using Unsplash API - README

This README file provides an overview and instructions for setting up and running the Unsplash Clone, a web application that utilizes the Unsplash API to fetch and display high-quality, royalty-free images.

## Features

- Search and browse a vast collection of high-resolution images from Unsplash.
- Infinite scrolling for seamless image browsing.
- Responsive design for optimal viewing on various devices.

## Prerequisites

To run the Unsplash Clone, you need the following:

- Node.js (v12 or higher)
- npm (Node Package Manager) or Yarn
- Unsplash API access key (obtainable from the Unsplash Developer Dashboard)

## Getting Started

Follow the steps below to set up and run the Unsplash Clone on your local machine:

1. Clone the repository:

   ```bash
   git clone https://github.com/Nikhil0723/unsplash-clone.git
   ```

2. Navigate to the project directory:

   ```bash
   cd unsplash-clone
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

4. Obtain an API access key from the [Unsplash Developer Dashboard](https://unsplash.com/developers).

5. Create a `.env` file in the root directory of the project and add the following line:

   ```bash
   REACT_APP_UNSPLASH_ACCESS_KEY=your-access-key
   ```

   Replace `your-access-key` with the API access key you obtained in the previous step.

6. Start the development server:

   ```bash
   npm start
   ```

   or

   ```bash
   yarn start
   ```

7. Open your web browser and navigate to `http://localhost:3000` to view the Unsplash Clone.

## Deployment

To deploy the Unsplash Clone to a production environment, you can use platforms like Netlify, Vercel, or GitHub Pages. Refer to their documentation for detailed instructions on deploying React applications.

When deploying, make sure to set the environment variable `REACT_APP_UNSPLASH_ACCESS_KEY` with your Unsplash API access key on the production environment as well.

## Contributing

Contributions to the Unsplash Clone are welcome! If you find any issues or would like to add new features, feel free to open an issue or submit a pull request.

## Acknowledgments

The Unsplash Clone is inspired by the official Unsplash website and utilizes the Unsplash API to provide image data. Special thanks to the Unsplash team for their fantastic work!

## Contact

For any additional questions or inquiries, please contact nikhilvishwakarma0723@gmail.com
