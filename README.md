# Top Courses

Top Courses is a React-based web application designed to display and filter a collection of courses. Users can explore courses by categories, view details, and "like" their favorite courses. The application is styled using Tailwind CSS for a modern and responsive UI.

---
**Live Demo:** [Top Courses](https://top-courses-vineet.netlify.app/)

---
## Features

- **Dynamic Filtering**: Filter courses by categories.
- **Like/Unlike Functionality**: Users can like or unlike courses, with visual feedback.
- **Responsive Design**: The app is fully responsive and works across devices.
- **Loading State**: Displays a spinner while fetching course data.
- **Toast Notifications**: Provides user feedback for actions like liking or unliking courses.

---

## Technologies Used

- **Frontend**: React, Tailwind CSS
- **Icons**: React Icons (e.g., `FcLike`, `FcLikePlaceholder`)
- **Notifications**: React Toastify

---

## Project Structure

```
Top Courses
├── public
├── src
│   ├── components
│   │   ├── Navbar.js
│   │   ├── Spinner.js
│   │   ├── Filter.js
│   │   ├── Cards.js
│   │   └── Card.js
│   ├── data.js
│   ├── App.js
│   └── index.js
├── package.json
└── README.md
```

---

## How It Works

1. **Navbar**: Displays the title of the app.
2. **Filter Component**: Allows users to filter courses by category.
3. **Cards Component**: Dynamically renders a list of courses based on the selected category.
4. **Card Component**: Displays individual course details with a like button.
5. **Spinner Component**: Shows a loading spinner while fetching data.

---

## Acknowledgments

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Toastify](https://fkhadra.github.io/react-toastify/)
- [React Icons](https://react-icons.github.io/react-icons/)

