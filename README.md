# Monster Rolodex 🎉

Welcome to my **very first project in ReactJS**! This project is super special to me as it marked the beginning of my journey with React. 🚀

![Monster Cards](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWtsNWtqaGE4MnV1dGRyOHJrY29iaW9iZ2xyaXp1MXB4bXh2MGd0biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/2m1llO5TwY5eqKUxOB/giphy.webp)

Monster Rolodex is a simple yet engaging web app that displays **cards featuring monsters** along with their **names** and **emails**. It also provides a **search bar** to filter through the monsters in real time.

---

## 🕹️ Features
- **Interactive Cards**: Displays fun monster avatars with their names and emails.
- **Search Functionality**: Allows users to search for monsters by name.
- **Responsive Design**: Built with CSS for a clean and responsive layout.

---

## 🔧 Technologies Used

- **ReactJS** – The backbone of this project, used for creating reusable components and managing state.
- **JavaScript (ES6+)** – For handling logic and asynchronous fetch requests.
- **CSS** – For styling the components.
- **JSONPlaceholder API** – Provides fake user data for populating the monster cards.

---

## 🚧 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Jaweria-B/monster-rolodex.git
   ```

2. Navigate to the project directory:
   ```bash
   cd monster-rolodex
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and visit:
   [http://localhost:3000](http://localhost:3000)

---

## 😎 What You’ll See

![Monster Cards](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmFkZzJ3MmFuYzN4ZmxkZnl6eW15bThuaW9xenM5OWM2YXB6Yms3aCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/165bgRHsluyhW/200.webp)

- A **title**: *Monsters Rolodex* 👽
- A **search bar**: Type in to find your favorite monster.
- A **list of cards**: Each card shows a monster’s avatar, name, and email address.

---

## 🔄 How It Works

1. **Data Fetching**:
   - Fetches data from `https://jsonplaceholder.typicode.com/users` using the `fetch` API inside a `useEffect` hook.

2. **State Management**:
   - Utilizes `useState` for managing:
     - `monsters` (API data)
     - `searchField` (user input)
     - `filteredMonsters` (monsters matching the search input)

3. **Dynamic Filtering**:
   - Filters monsters in real-time based on the user’s search input.

4. **Reusable Components**:
   - **SearchBox**: Handles the search input.
   - **CardList**: Renders the filtered list of monster cards.

---

## 🎨 Why This Project is Special to Me

This is my first step into React, and it’s been a fantastic learning experience! Building the Monster Rolodex helped me:
- Understand the power of **components**.
- Grasp the importance of **state management** and **props**.
- Appreciate how React simplifies creating dynamic web apps.

Here’s to many more React projects in the future! 🌟

---

## 🎮 Live Demo

Check out the live version of Monster Rolodex:
[**Monster Rolodex App**](https://monsters-rolodex.vercel.app)

---

## 🔎 Explore the Code

Dive into the source code to learn more:
[**GitHub Repository**](https://github.com/Jaweria-B/monster-rolodex)

---

## 🌟 Show Your Support

If you enjoyed this project, feel free to **star the repo** or leave a suggestion. Your feedback means a lot! 😍

---

## 🔧 Future Enhancements
- Add more interactive features like monster details pop-ups.
- Introduce themes and animations for a better user experience.
- Improve responsiveness and design aesthetics.

