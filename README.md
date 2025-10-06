# Welcome to the Report Clarity Agent Project

## Project Overview

This project is a web application built using Vite, React, TypeScript, and Tailwind CSS. It serves as a platform for intelligent BI documentation, leveraging Supabase for backend services.

## Deployment on Streamlit

To deploy this project on Streamlit while maintaining the same design and pages, follow these steps:

1. **Convert React Components**: Rewrite the existing React components using Streamlit's API. Streamlit does not support React directly, so you will need to create equivalent components using Streamlit's layout and component functions.

2. **Replicate Design and Functionality**: Use Streamlit's layout options to replicate the design of the existing application. Ensure that all UI elements are represented accurately.

3. **State Management**: Utilize Streamlit's session state to manage application state. This will help in maintaining the state across user interactions.

4. **Data Fetching**: Implement API calls to fetch data from Supabase. Ensure that the environment variables from the `.env` file are accessible in the Streamlit app.

5. **Deployment Process**: Update the deployment process to utilize Streamlit's deployment options, such as Streamlit Sharing or deploying on a cloud platform.

6. **Testing**: Thoroughly test the application to ensure that all functionalities are working as expected after the migration.

## Project Structure

- **.env**: Contains environment variables for the application, including Supabase project ID, publishable key, and URL.
- **components.json**: Configuration for components, including Tailwind CSS settings and aliases for paths.
- **eslint.config.js**: Configures ESLint for the project, extending recommended rules and specifying file patterns and plugins.
- **index.html**: Main HTML file serving as the entry point for the application.
- **package.json**: Contains metadata about the project, including dependencies and scripts.
- **README.md**: Documentation and instructions for the project.
- **src/**: Contains the main application code, including components, hooks, and pages.

## Technologies Used

- Vite
- React
- TypeScript
- Tailwind CSS
- Supabase

## Getting Started

To get started with the project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone <YOUR_GIT_URL>
   ```

2. Navigate to the project directory:
   ```sh
   cd report-clarity-agent-main
   ```

3. Install the necessary dependencies:
   ```sh
   npm install
   ```

4. Start the development server:
   ```sh
   npm run dev
   ```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.