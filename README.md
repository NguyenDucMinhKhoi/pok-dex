# Pokédex

A simple and interactive web application that displays Pokémon information using data fetched from the [PokeAPI](https://pokeapi.co/). This project is designed to practice and demonstrate skills in web development, API integration, and creating responsive interfaces.

---

## Features
- **View Pokémon List**: Browse through a list of Pokémon with their names and images.
- **Search Pokémon**: Find a specific Pokémon by its name.
- **Detailed View**: Click on a Pokémon to see its detailed information, including:
  - Types
  - Stats (HP, Attack, Defense, etc.)
  - Abilities
  - Sprites

---

## Technologies Used
- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript (Vanilla/React.js, if applicable)
- **API**:
  - [PokeAPI](https://pokeapi.co/)
- **Other Tools**:
  - Git/GitHub for version control
  - Any additional libraries or frameworks used (e.g., Bootstrap, Tailwind CSS)

---

## Installation and Setup

Follow these steps to set up and run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/NguyenDucMinhKhoi/pok-dex.git
```
### 2. Navigate to the Project Directory
```bash
cd pok-dex
```

### 3. Install Dependencies
If the project uses a package manager like npm, run:
```bash
npm install
```

### 4. Start the Application
For a development server:
```bash
npm start
```

Or if the project is static:
1. Open `index.html` in your browser.
2. Alternatively, use a local development server like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code.

---

## Usage
1. **Browse Pokémon**: Scroll through the list of Pokémon displayed on the homepage.
2. **Search for Pokémon**: Use the search bar to find your favorite Pokémon.
3. **View Details**: Click on a Pokémon to view its detailed stats, abilities, and more.

---

## API Integration
This project integrates with [PokeAPI](https://pokeapi.co/) to fetch real-time data about Pokémon. Below are the main endpoints used:
- **List Pokémon**: `https://pokeapi.co/api/v2/pokemon?limit=100`
- **Get Pokémon Details**: `https://pokeapi.co/api/v2/pokemon/{pokemon_name}`

---

## Screenshots
_Add screenshots or GIFs of your application here to visually represent the project._

---

## Folder Structure
```
pok-dex/
│
├── public/             # Static files (images, icons, etc.)
├── src/                # Source code
│   ├── components/     # Reusable UI components
│   ├── pages/          # Main pages
│   ├── styles/         # CSS files
│   └── index.js        # Entry point
├── package.json        # Dependencies and scripts
└── README.md           # Project documentation
```

---

## Future Improvements
- Add pagination for the Pokémon list.
- Implement filtering by type (e.g., Fire, Water, Grass).
- Enhance UI/UX with animations and responsiveness.
- Add offline support with Progressive Web App (PWA) features.

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add some feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements
- [PokeAPI](https://pokeapi.co/) for providing Pokémon data.
- Any frameworks, libraries, or tools used in the project.
- Special thanks to contributors and testers.
