# BookVerse — Modern E-Commerce Book Store 📚

A sleek, high-performance Full-Stack web application developed for my **Diploma Exam at IT-Step Academy (July 2024)**. It features real-time data interaction, allowing users to manage a book collection with persistent updates via a RESTful API simulation.

---

### 📋 Project Overview
BookVerse is a modern bookstore platform built to demonstrate advanced **React patterns**. Unlike static frontend sites, this project communicates with a **JSON Server** to perform CRUD operations, providing a realistic user experience where changes to the cart and book list are handled via API requests.

---

### 🛠 Tech Stack

* **Core:** React.js (Functional Components, Hooks)
* **Data Management:** JSON Server (REST API Mocking)
* **State Management:** React Context API / Redux
* **API Interaction:** Axios / Fetch API (GET, POST, DELETE)
* **Styling:** HTML5 & Pure CSS3 (Fully Responsive)
* **Animations:** Framer Motion / AOS
* **Routing:** React Router DOM

---

### 🌟 Key Features

#### 1. Dynamic Data Interaction
* **Live API Requests:** The app fetches the book catalog dynamically from a `db.json` file.
* **Persistence:** Adding or removing items sends requests to the server, ensuring data consistency across sessions.

#### 2. Advanced Filtering & Sorting
* **Real-time Search:** Instant filtering by title or author as you type.
* **Multi-Criteria Sorting:** Sort by Price (Low/High), Release Date, or Alphabet.
* **Category System:** Genre-based navigation for a better user experience.

#### 3. User Experience
* **Authentication:** Dedicated Login and Register pages with state-driven session management.
* **Smart Cart:** Instant UI updates synchronized with the backend simulation.

---

### 🏗 Logic Flow
1.  **Fetching Data:** On page load, `useEffect` triggers a GET request to the JSON server to populate the store.
2.  **Filter Engine:** Processes the book array locally for instant, lag-free search results.
3.  **Cart Sync:** POST/PATCH requests are sent to the server on every change; UI updates only after a successful response.

---

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/bookstore-react.git](https://github.com/your-username/bookstore-react.git)
Install dependencies:

Bash
npm install
Start the JSON Server (Backend):
Open a separate terminal:

Bash
npx json-server --watch db.json --port 5000
Start the React App (Frontend):

Bash
npm start
🎓 Diploma Project
Developed as a final project for IT-Step Academy.

Date: July 2024

Developer: Abdullo Kamoliddinov
