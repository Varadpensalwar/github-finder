# GitHub User Finder

A sleek and responsive web application that allows you to search for GitHub users and explore their profiles, including their repositories, followers, and other public information.

## Features

- **User Search**: Search for any GitHub user by their username
- **Profile Display**: View comprehensive user information including:
  - Profile picture and basic info
  - Bio, location, and join date
  - Follower and following counts
  - Public repository count
  - Company and website links
  - Twitter/X profile (if available)
- **Repository Showcase**: Display the user's latest repositories with:
  - Repository name and description
  - Programming language
  - Star and fork counts
  - Last updated date
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Dark Theme**: Modern dark UI with purple accent colors

## Demo

The application comes pre-loaded with a demo search for the username "Varadpensalwar" to showcase its functionality.

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS custom properties and flexbox
- **JavaScript (ES6+)**: Async/await for API calls and DOM manipulation
- **GitHub API**: Fetches real-time user and repository data
- **Font Awesome**: Icons for enhanced visual appeal

## Quick Start

Simply open [`index.html`](index.html) in your web browser and start searching for GitHub users!

## Getting Started

### Prerequisites

- A modern web browser
- Internet connection (for GitHub API calls and Font Awesome icons)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Varadpensalwar/github-finder.git
   ```

2. Navigate to the project directory:
   ```bash
   cd github-finder
   ```

3. Open [`index.html`](index.html) in your web browser or serve it using a local server.

### Using a Local Server

For the best experience, serve the application using a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Usage

1. Enter a GitHub username in the search box
2. Click the "Search" button or press Enter
3. View the user's profile information and repositories
4. Click on repository names to visit them on GitHub
5. Use the "View Profile" button to visit the user's GitHub profile

## File Structure

```text
github-finder/
├── index.html          # Main HTML structure
├── style.css           # Styling and layout
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## API Usage

This application uses the [GitHub REST API](https://docs.github.com/en/rest) to fetch user data:

- **User Information**: `https://api.github.com/users/{username}`
- **User Repositories**: `https://api.github.com/users/{username}/repos`

No authentication is required, but the API has rate limits for unauthenticated requests (60 requests per hour per IP address).

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Any modern browser with ES6+ support

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Varad Pensalwar**
- GitHub: [@Varadpensalwar](https://github.com/Varadpensalwar)

## Acknowledgments

- [GitHub API](https://docs.github.com/en/rest) for providing the data
- [Font Awesome](https://fontawesome.com/) for the beautiful icons
- The open-source community for inspiration and best practices