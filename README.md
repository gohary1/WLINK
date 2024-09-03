# wlink

![Alt text](docs/assets/imgs/datacenter)

wlink is a dynamic web application built with Angular, featuring stunning animations and visualizations. It provides an interactive user experience with a robust contact system.

## Features

- **Angular-powered**: Utilizes the latest Angular framework for a responsive and efficient front-end.
- **Animations & Visualizations**: Incorporates eye-catching animations and data visualizations to enhance user engagement.
- **Smart Contact System**: 
  - Sends confirmation emails to users upon form submission.
  - Notifies the website manager of new inquiries.
  - Powered by a custom .NET C# backend using MailKit.
- **Data Validation**: Implements regex-based validation for contact form inputs, ensuring data integrity before submission.

![Feature Showcase](path/to/feature-showcase.gif)

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- Angular CLI
- .NET 5.0 or later (for backend)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/wlink.git
   ```

2. Navigate to the project directory:
   ```
   cd wlink
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   ng serve
   ```

5. Open your browser and visit `http://localhost:4200`

## Backend Setup

1. Navigate to the backend directory:
   ```
   cd backend
   ```

2. Restore .NET packages:
   ```
   dotnet restore
   ```

3. Run the backend server:
   ```
   dotnet run
   ```

## Contact Form Validation

The contact form uses regex patterns to validate user inputs before submission. This ensures that only properly formatted data is sent to the backend. Key validations include:

- Email format
- Phone number format
- Name (no special characters)
- Message length

Example regex pattern for email validation:
```typescript
const emailPattern = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,4}$/;
```

## Usage

[Add screenshots or GIFs demonstrating key features]

![Usage Example](path/to/usage-example.gif)

## Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to submit pull requests, report issues, or request features.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Angular team for the fantastic framework
- MailKit for robust email functionality
