⚛️ ElementX — Interactive Periodic Table

«An interactive periodic table where chemical elements become animated visual experiences, powered by HTML, CSS, and JavaScript.»

ElementX is a browser-based chemistry explorer that lets you discover all 118 chemical elements, explore their properties, compare atomic structures, and search through the periodic table using a modern dark interface with neon-purple accents.

No installation. No backend server. Just your browser and the science of elements.

---

✨ Features

- ⚛️ Interactive Periodic Table — Explore all 118 chemical elements.
- 🧪 Element Explorer — View element names, symbols, atomic numbers, atomic masses, and chemical families.
- 🌀 Animated Atom Visuals — Explore elements with animated orbital-style graphics.
- 🔬 Atomic Structure Comparison — Compare two elements side by side.
- ⚡ Electron Shell Model — View a simplified distribution of electrons across atomic shells.
- 🔍 Live Search — Find elements by name, symbol, or atomic number.
- 🎨 Chemical Family Filters — Filter elements by their chemical classification.
- 🎲 Surprise Me — Discover a randomly selected element.
- 📊 Element Information — Explore basic properties and educational descriptions.
- 🌌 Modern Dark UI — Futuristic interface with purple and cyan accents.
- 📱 Responsive Layout — Adapts to desktop and mobile screens.
- 🚀 Single-File Application — The complete application is contained in one HTML file.

---

🖥️ User Interface

ElementX provides an interactive periodic table alongside an element information panel, animated atom graphics, and an atomic comparison tool.

┌───────────────────────────────────────────────────────────┐
│  ⚛ ELEMENTX                     INTERACTIVE ELEMENT LAB   │
├───────────────────────────────────────────────────────────┤
│                                                           │
│  Meet the elements.                                       │
│  See the science.                                         │
│                                                           │
│  [ Search elements... ] [ Family Filter ] [ Surprise Me ] │
│                                                           │
├─────────────────────────────────┬─────────────────────────┤
│  PERIODIC TABLE                 │  ELEMENT EXPLORER       │
│                                 │                         │
│  H                         He   │       Animated Atom     │
│  Li Be             B C N O F Ne │                         │
│  Na Mg             Al Si P S... │  Carbon                 │
│                                 │  Atomic Number: 6       │
│  ...                            │  Atomic Mass: 12.011 u  │
│                                 │                         │
│                                 │  ELECTRON SHELL MODEL   │
│                                 │  Shell 1: 2             │
│                                 │  Shell 2: 4             │
├─────────────────────────────────┼─────────────────────────┤
│                                 │  COMPARE ELEMENTS       │
│                                 │  [Carbon] [Oxygen]      │
│                                 │  Atomic Number / Mass   │
└─────────────────────────────────┴─────────────────────────┘

The diagram is a simplified illustration of the interface.

---

🚀 Quick Start

1. Clone the Repository

git clone https://github.com/rsamwilson2323-cloud/ElementX.git

2. Enter the Project Folder

cd ElementX

3. Run ElementX

The main application is:

ElementX.html

Open the HTML file in a modern browser to start exploring.

Alternatively, rename it to "index.html" and start a local server:

python -m http.server 8000

Then visit:

http://localhost:8000

Recommended Browsers

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Other modern browsers that support HTML5, CSS3, and JavaScript

Note: The application uses standard browser technologies and does not require a backend server or external JavaScript libraries.

---

🧪 Exploring the Elements

⚛️ 1. Interactive Periodic Table

Browse the periodic table and select any element to explore its properties.

- View the atomic number and chemical symbol.
- Identify the element's name and family.
- Explore the element's position in the periodic table.
- View its approximate atomic mass.
- Select different elements to update the information panel.

The table includes all 118 recognized chemical elements.

🔍 2. Search Elements

Use the search field to find an element instantly.

Search by:

- Element name — "Carbon"
- Chemical symbol — "Fe"
- Atomic number — "79"

The table highlights matching elements as you type.

🎨 3. Filter by Chemical Family

Use the family filter to explore specific groups of elements.

Available categories include:

- Alkali metals
- Alkaline earth metals
- Transition metals
- Post-transition metals
- Metalloids
- Nonmetals
- Halogens
- Noble gases
- Lanthanides
- Actinides

Choose All families to restore the complete periodic table.

🌀 4. Animated Atom Visuals

Each selected element features an animated orbital-style visual.

- Explore the selected element through a changing visual display.
- View its chemical symbol at the center.
- Switch between elements to update the visual.
- Experience a futuristic science-lab interface.

The orbital graphics are illustrative animations, not physically accurate simulations of electron orbitals.

🔬 5. Atomic Structure Comparison

Compare two elements side by side using the comparison panel.

The comparison includes:

- Atomic number
- Atomic mass
- Chemical family
- Simplified electron shell distribution

For example, compare Carbon and Oxygen to explore how their atomic numbers, masses, and electron distributions differ.

🎲 6. Surprise Me

Use Surprise Me to discover a randomly selected element.

This feature is useful for:

- Learning about unfamiliar elements
- Exploring the periodic table interactively
- Practicing element recognition
- Discovering different chemical families

↶ 7. Reset View

Use Reset to clear the current search and family filter and return to the default selected element.

---

🎨 Interface Design

ElementX uses a futuristic dark theme designed for a clean and immersive learning experience.

Design Element| Description
Background| Deep navy and dark blue
Primary Accent| Neon purple
Secondary Accent| Cyan
Element Cards| Color-coded chemical families
Typography| Clean, readable sans-serif
Animation| CSS-powered orbital effects
Layout| Responsive table and information panels

The visual design combines scientific information with modern web aesthetics.

---

🧬 Element Information

Each element includes a collection of basic properties.

Property| Description
Atomic Number| Number of protons in the nucleus
Chemical Symbol| Abbreviated symbol of the element
Element Name| Commonly recognized element name
Atomic Mass| Approximate standard atomic weight or representative mass
Chemical Family| Broad classification of the element
Period| Row position in the periodic table
Group| Column position in the periodic table
Electron Shells| Simplified educational shell distribution

Educational note: Electron shell distributions in this version use a simplified model. They are not intended to replace accurate electron configurations, particularly for transition metals and heavier elements. Some radioactive elements have representative mass numbers rather than standard atomic weights.

---

🛠️ Technology Stack

Technology| Purpose
🌐 HTML5| Application structure
🎨 CSS3| Styling, layout, animations, and responsive design
⚡ JavaScript| Element data, search, filters, and interactions
🌀 CSS Animations| Animated orbital-style visuals
📊 JavaScript Arrays| Storage of element information
🖱️ DOM Events| Element selection and interactive controls
📱 CSS Media Queries| Mobile-friendly layout

---

📂 Project Structure

ElementX/
│
├── 📄 ElementX.html
└── 📄 README.md

If you prefer a conventional website entry point, you can rename "ElementX.html" to "index.html".

"ElementX.html"

Contains the complete application, including:

- HTML interface
- CSS styling and responsive layout
- Animated atom visuals
- Periodic table for 118 elements
- Element information panel
- Chemical family filters
- Live search
- Atomic comparison controls
- Simplified electron shell calculations
- Random element selection
- Reset functionality

"README.md"

Contains the project overview, features, setup instructions, usage guide, technology stack, and documentation.

---

🏗️ How It Works

ElementX combines a structured element dataset with JavaScript-powered interactions.

User Opens ElementX
        ↓
Load Periodic Table Data
        ↓
Render the Element Cards
        ↓
User Selects or Searches an Element
        ↓
Find Matching Element Data
        ↓
Update Element Information Panel
        ↓
Display Animated Atom and Shell Model
        ↓
Compare Elements or Explore Another

The periodic table is generated dynamically from JavaScript data. Selecting an element updates its information panel, while search and family filters highlight matching elements.

The comparison panel retrieves the selected elements and displays their properties side by side.

---

🔐 Privacy & Data

- No project-specific backend server is required.
- No database is required.
- Element information is stored in the application's JavaScript dataset.
- Search and comparison operations run locally in the browser.
- The application does not require an account or login.
- No external JavaScript library is required for the core interface.

---

💻 Requirements

- A modern web browser
- JavaScript enabled
- Basic HTML5 and CSS3 support

No Node.js, Python installation, game engine, database, or package manager is required to open the standalone HTML file.

---

🔮 Future Improvements

Potential enhancements for future versions include:

□ Interactive 3D atom models using Three.js
□ Accurate electron configurations
□ Animated electron and orbital visualizations
□ Element discovery quiz
□ Chemical property comparison charts
□ Melting and boiling point information
□ Density and electronegativity data
□ Periodic trends visualization
□ Isotope explorer
□ Element category legend
□ Advanced filters and sorting
□ Element favorites and bookmarks
□ Searchable element history
□ Mobile-first interactive controls
□ Dark and light themes
□ Educational challenges and achievements
□ Offline installation as a Progressive Web App

These are potential future enhancements and are not claimed as existing features.

---

👨‍💻 Author

Sam Wilson

B.E. CSE — Artificial Intelligence & Machine Learning

GitHub:
https://github.com/rsamwilson2323-cloud

---

⭐ Repository

ElementX — Interactive Periodic Table

https://github.com/rsamwilson2323-cloud/ElementX

If you enjoy the project, consider giving the repository a ⭐ on GitHub!

---

📜 License

No license information was provided with this project. Add a "LICENSE" file and update this section if you choose to distribute ElementX under a specific open-source license.

---

🚀 Quick Start

git clone https://github.com/rsamwilson2323-cloud/ElementX.git
cd ElementX

Open "ElementX.html" in your browser and start exploring the periodic table.

---

⚛️ Explore → 🔬 Compare → 🧪 Discover

ElementX — Explore the elements. Discover the science.
