# Quote Machine Web Application 💭

![Quote Machine Screenshot](/public/quote.png)

The Quote Machine is a simple web application built using Next.js that provides users with inspirational and thought-provoking quotes. It fetches random quotes from an external API and allows users to display a new quote with a single click. Users can also share their favorite quotes on social media.

## Features

- Randomly fetches inspirational quotes from an external API.
- Dynamic background color changes with each new quote.
- Allows users to tweet their favorite quotes.
- Provides an option to post quotes on Tumblr.
- User-friendly and responsive design.

## Getting Started

Follow these instructions to run the Quote Machine web application locally on your machine.

### Prerequisites

- Node.js: Make sure you have Node.js installed on your system. If not, you can download it from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/quote-machine.git
   ```

2. Change to the project directory:

   ```bash
   cd quote-machine
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

### Configuration

1. Create a `.env.local` file in the root directory of the project.

2. Add your API key to the `.env.local` file in the following format:

   ```env
   REACT_APP_API_KEY=your_api_key_here
   ```

### Running the Application

To start the development server and run the Quote Machine app:

```bash
npm start
```

The application will be accessible in your browser at `http://localhost:3000/`.

### Usage

- Click the "New quote" button to display a new inspirational quote.
- Share your favorite quotes on Twitter by clicking the "Tweet" button.
- Share quotes on Tumblr using the "Tumblr" button.

## Contributing

Contributions are welcome! If you'd like to contribute to the Quote Machine app, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them with clear messages.
- Create a pull request to merge your branch into the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was created as a part of a freeCodeCamp React web development course.
- The Quote Machine relies on the "api-ninjas" API for fetching quotes.
