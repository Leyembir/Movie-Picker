# Home Cinema Booking System

## Project Overview

This project is a simple yet functional Home Cinema Booking System designed for personal use. It allows users to browse a library of movies and select seats for viewing in a home cinema setup. The system is built with HTML, CSS, JavaScript, and integrates with movie APIs for a dynamic movie selection experience.

## Features

- **Movie Browsing:** Users can browse through a dynamically fetched list of movies.
- **Seat Selection:** A U-shaped seat selection interface allows for up to 4 seats to be chosen.
- **Single Seat Booking:** Users can select a single seat and book it for their chosen movie.
- **Dynamic Movie Data:** Movie information is fetched from The Movie Database (TMDb) API.

## Future Enhancements

- **Movie Polling System:** A new feature will allow household members to pick movies they wish to watch. A voting system will then be implemented for everyone to vote on the movie selection. This democratic approach ensures that the movie choice reflects the preferences of the majority.
- **Seat Allocation Post-Poll:** Once the movie poll ends, the seat selection process will be initiated, leveraging the existing seat chooser functionality. This ensures that seat selection is fair and only commences once the movie is decided.

## Setup Instructions

1. **Clone the Repository**

git clone https://github.com/Leyembir/movie-picker.git
2. **Open `index.html`**

Simply open the `index.html` file in a modern web browser to start using the application.

3. **API Key Configuration**

To fetch movie data, you'll need an API key from TMDb:

- Sign up at [TMDb](https://www.themoviedb.org/) and obtain your API key.
- Replace `'YOUR_API_KEY'` in the `script.js` file with your actual TMDb API key.

## Usage

- Browse the list of movies fetched from the TMDb API.
- Select a movie and choose your preferred seat.
- Confirm your booking by clicking the "Book Seat" button.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

