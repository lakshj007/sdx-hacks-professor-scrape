# SDX Hacks - Professor Scraper

A web application that helps students find and evaluate professors based on various criteria. This project was developed for SD Hacks.

## Features

- **Professor Search**: Find professors based on name, department, or research interests.
- **Profile Analysis**: View detailed profiles of professors including their research, publications, and contact information.
- **Matching System**: Get personalized professor recommendations based on your interests and academic goals.
- **Web Scraping**: Automatically gathers and updates professor information from university websites.

## Installation

### Prerequisites

- Python 3.8+
- Node.js 14+
- npm or yarn

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd rizzard-sdx-helixhack/backend
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd rizzard-sdx-helixhack/frontend
   ```
2. Install the dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

## Usage

### Running the Backend

```bash
cd rizzard-sdx-helixhack/backend
uvicorn app.main:app --reload
```

### Running the Frontend

```bash
cd rizzard-sdx-helixhack/frontend
npm run dev
# or
yarn dev
```

Visit `http://localhost:3000` in your browser to view the application.

## Project Structure

- `rizzard-sdx-helixhack/backend/` - Contains the FastAPI backend
  - `app/` - Main application code
  - `data/` - Data files and scripts
  - `db/` - Database schema and migrations
- `rizzard-sdx-helixhack/frontend/` - Contains the Next.js frontend
  - `app/` - Next.js app directory
  - `components/` - Reusable React components
  - `public/` - Static files

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributors

- [Your Name](https://github.com/yourusername)

## Acknowledgments

- SD Hacks for the opportunity to build this project
- All the open-source libraries and tools used in this project
