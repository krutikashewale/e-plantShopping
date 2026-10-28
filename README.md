# Paradise Nursery Shopping Application

Paradise Nursery is an online plant shopping web application that provides plant enthusiasts with a seamless e-commerce experience. Built using React and Redux Toolkit, this application allows users to browse an extensive catalog of indoor and outdoor plants categorized by their unique benefits, manage their shopping cart, and calculate real-time order costs.

---

## 🌿 Project Overview

The **Paradise Nursery Shopping Application** was developed as the final project for the IBM Coursera Front-End Development with React course. It emphasizes interactive modern UI design, robust component hierarchy, dynamic state management, and real-time shopping cart calculations.

---

## ✨ Features

- **Interactive Landing Page**:
  - Welcoming hero section with atmospheric background imagery.
  - Informative **About Us** section highlighting the company mission, values, and dedication to botanical wellness.
  - Intuitive **Get Started** button leading directly to the plant selection catalog.

- **Categorized Plant Catalog**:
  - Organized into distinct botanical categories:
    - *Air Purifying Plants* (e.g., Snake Plant, Spider Plant, Peace Lily)
    - *Aromatic Fragrant Plants* (e.g., Lavender, Jasmine, Rosemary)
    - *Insect Repellent Plants* (e.g., Oregano, Marigold, Basil)
    - *Medicinal Plants* (e.g., Aloe Vera, Peppermint, Chamomile)
    - *Low Maintenance Plants* (e.g., ZZ Plant, Pothos, Cast Iron Plant)
  - Every plant card includes an image, title, detailed description, and unit price.
  - "Add to Cart" button that dynamically disables and updates text once added to prevent duplicate additions.

- **Responsive Navigation Bar**:
  - Persistent navigation across catalog and cart views.
  - Branding with company name and motto: *"Where Green Meets Serenity"*.
  - Direct navigation links to **Plants** and **Cart**.
  - Dynamic cart counter badge displaying the total quantity of items in real-time.

- **Full Shopping Cart Functionality**:
  - Detailed breakdown of each selected plant (thumbnail, name, unit price, quantity, and subtotal).
  - Increment (`+`) and decrement (`-`) quantity controls with automated cart recalculation.
  - Item deletion button to immediately remove plants from the cart.
  - Dynamic total cart cost calculation.
  - **Continue Shopping** button to return to the catalog.
  - **Checkout** button with an interactive confirmation alert (*"Coming Soon! Checkout will be available soon."*).

---

## 🛠️ Tech Stack

- **React 18** (Functional components, Hooks: `useState`, `useEffect`)
- **Redux Toolkit (`@reduxjs/toolkit`)** (Global cart state management with `createSlice`)
- **React-Redux** (`useSelector`, `useDispatch`)
- **Vite** (Build tooling and fast development server)
- **Vanilla CSS3** (Responsive styling, CSS Grid, Flexbox, transitions, and hover effects)

---

## 📂 Project Structure

```text
├── public/                 # Static assets
├── src/
│   ├── assets/             # Images and local media
│   ├── AboutUs.css         # Styling for About Us section
│   ├── AboutUs.jsx         # About Us company info component (Task 2)
│   ├── App.css             # Main styling & landing page background (Task 3)
│   ├── App.jsx             # Main application component & landing page (Task 4)
│   ├── CartItem.css        # Styling for Shopping Cart view
│   ├── CartItem.jsx        # Shopping Cart component with quantity controls (Task 7)
│   ├── CartSlice.jsx       # Redux slice managing cart state & reducers (Task 5)
│   ├── ProductList.css     # Styling for product cards, grid, and navigation
│   ├── ProductList.jsx     # Product listing catalog with categories (Task 6)
│   ├── index.css           # Global CSS resets
│   ├── main.jsx            # Application entry point with Redux Provider
│   └── store.js            # Redux store configuration
├── index.html              # HTML template
├── package.json            # Project dependencies and npm scripts
└── README.md               # Project documentation (Task 1)
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (v16 or higher) and `npm` installed.

### Installation

1. Clone or download this repository:
   ```bash
   git clone <repository-url>
   cd "IBM plant"
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser to view the application.

---

## 📝 Grading Criteria & Tasks

| Task | File | Description |
|------|------|-------------|
| **Task 1** | `README.md` | Contains project name and full details. |
| **Task 2** | `AboutUs.jsx` | Company details, vision, and mission. |
| **Task 3** | `App.css` | Background image and landing page styling. |
| **Task 4** | `App.jsx` | Landing page with company name and "Get Started" button. |
| **Task 5** | `CartSlice.jsx` | Redux slice managing items, `addItem`, `removeItem`, and `updateQuantity`. |
| **Task 6** | `ProductList.jsx` | Houseplants grouped into categories, Add-to-Cart buttons, disabled state, and dynamic cart icon count. |
| **Task 7** | `CartItem.jsx` | Cart items, unit price, quantity increment/decrement, subtotal, total amount, checkout, and continue shopping. |

---

## 📄 License

This project is licensed under the MIT License.