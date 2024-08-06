# Product Hunt Clone

A simplified clone of the Product Hunt homepage, built using Next.js, Mantine UI, and Tailwind CSS. This project focuses on replicating the UI up to the "Upvoted" button, ensuring a responsive and mobile-friendly design.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Demo

![pic1](https://github.com/user-attachments/assets/42e42197-551f-41bc-8139-31511666c7fa)

## Features

- **Upvote Functionality**: Click the button to toggle its state between "Upvote" and "Upvoted".
- **Responsive Design**: The layout is mobile-friendly and adapts to different screen sizes.
- **Modern UI**: Utilizes Mantine UI components for a clean and professional appearance.
- **Tailwind CSS**: Provides utility-first CSS for rapid styling and responsive design.

## Technologies Used

- [Next.js](https://nextjs.org/): A React framework for server-side rendering and generating static websites.
- [Mantine UI](https://mantine.dev/): A fully featured React components library with built-in accessibility.
- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (>= 14.0.0)
- [npm](https://www.npmjs.com/) (>= 6.0.0)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/product-hunt-clone.git
    cd product-hunt-clone
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Run the development server**:
    ```bash
    npm run dev
    ```

4. **Open your browser**:
    Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## Project Structure

```bash
product-hunt-clone/
├── components/
│   └── ProductCard.js    # Component for the product card
├── pages/
│   ├── _app.js           # Custom App component with MantineProvider
│   └── index.js          # Main page rendering the ProductCard
├── public/
│   └── images/           # Placeholder for images
├── styles/
│   └── globals.css       # Global styles, including Tailwind CSS imports
├── .gitignore            # Files to ignore in git
├── tailwind.config.js    # Tailwind CSS configuration
├── postcss.config.js     # PostCSS configuration
├── package.json          # Project metadata and dependencies
└── README.md             # Project information
