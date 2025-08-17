# Public Domain Book Library

A one-page responsive web application to search, browse, and download public-domain books from Project Gutenberg, Open Library, and Internet Archive. Built with vanilla JavaScript, HTML5, and CSS3, this tool empowers readers, researchers, and developers to discover classic works in multiple languages—no backend required.

---

## Table of Contents

- [Demo](#demo)  
- [Features](#features)  
- [Technologies](#technologies)  
- [Project Structure](#project-structure)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  
- [Author](#author)  

---

## Demo

![Search Results Screenshot](docs/demo.png)

Try the live version on GitHub Pages:  
https://bocaletto-luca.github.io/public-domain-book-library

---

## Features

- Search public-domain books by title, author, or general query  
- Fetch results from three major APIs:
  - Project Gutenberg (via Gutendex)  
  - Open Library  
  - Internet Archive  
- Filter by language (English, Italian, Spanish, French, German, Latin, etc.)  
- Responsive grid layout with paginated results  
- Quick “Read / Download” links to EPUB, plain text, or online viewer  
- SEO-friendly meta tags and Open Graph integration  
- Zero external dependencies—pure HTML, CSS, and JavaScript  

---

## Technologies

- HTML5 & CSS3 (Flexbox & CSS Grid)  
- Vanilla JavaScript (ES6+)  
- Public APIs:
  - Gutendex (Project Gutenberg)  
  - Open Library Search API  
  - Internet Archive AdvancedSearch API  
- GitHub Pages for static hosting  

---

## Project Structure

```
public-domain-book-library/
├── index.html       # Single-page application
├── README.md        # Project overview and setup instructions
└── LICENSE          # MIT License
```

---

## Getting Started

### Prerequisites

All you need is a modern web browser. No server, database, or build tools required.

### Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/bocaletto-luca/public-domain-book-library.git
   ```
2. Open `index.html` in your favorite browser  
   ```bash
   cd public-domain-book-library
   open index.html
   ```

Alternatively, deploy on GitHub Pages or any static-site host:

1. Push your code to a GitHub repo named `public-domain-book-library`.  
2. In the repo’s **Settings → Pages**, select the `main` branch and `/ (root)` folder.  
3. Save and visit `https://<your-username>.github.io/public-domain-book-library`.

### Usage

1. Select a data source: **Project Gutenberg**, **Open Library**, or **Internet Archive**.  
2. Choose your search field: **Any Field**, **Title**, or **Author**.  
3. Enter a keyword or phrase.  
4. (Optional) Filter by language.  
5. Click **Search** to load page 1 of results.  
6. Navigate with **Previous** and **Next** buttons.  
7. Click **Read / Download** to open or save the book.

---

## Contributing

Contributions are welcome! To propose changes:

1. Fork this repository.  
2. Create a feature branch: `git checkout -b feature/YourFeature`.  
3. Commit your changes: `git commit -m "Add YourFeature"`.  
4. Push to your fork: `git push origin feature/YourFeature`.  
5. Submit a Pull Request describing your work.

Please adhere to the existing code style and include clear commit messages.

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## Author

**Bocaletto Luca**  
- GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  
- Portfolio: https://bocaletto-luca.github.io  
- Contact: bocaletto.luca@example.com  

Feel free to reach out if you have questions or ideas. Happy reading!
