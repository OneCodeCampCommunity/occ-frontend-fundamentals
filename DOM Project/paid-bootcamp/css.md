```css
/* General Styling */
* {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
  padding: 0;
}

body {
  background-color: #a8dadc;
  min-height: 100vh; /* Viewport Height */
}

#title {
  font-size: 4rem;
  text-align: center;
  margin: 3rem;
}

form {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  margin: 2rem;
}

/* FORM */
form input,
form button {
  padding: 0.5rem;
  font-size: 2rem;
  border: none;
  background: #fffffc;
}

form input {
  width: 350px;
}

form button {
  background: #fffffc;
  cursor: pointer;
  transition: all 0.3s ease;
}

form button:hover {
  background: #457b9d;
  color: #fffffc;
}

/* TODO CONTAINER */
.todo-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.todo-list {
  min-width: 30%;
  list-style: none;
}

.todo {
  margin: 0.5rem;
  background: #fffffc;
  font-size: 1.5rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  transition: all 0.5s ease;
}

.todo-item {
  padding: 0rem 0.5rem;
}

.todo li {
  flex: 1;
}

i {
  pointer-events: none;
}

/* BUTTONS */
.trash-btn,
.complete-btn {
  background: #fe4a49;
  color: white;
  border: none;
  padding: 1rem;
  cursor: pointer;
  font-size: 1rem;
}

.complete-btn {
  background-color: #06d6a0;
}

.completed {
  text-decoration: line-through;
  opacity: 0.5;
}

.fall {
  transform: translateY(8rem) rotateZ(20deg);
  opacity: 0;
}

/* FILTER */
select {
  -webkit-appearance: none;
  -moz-appearance: none;
  -ms-appearance: none;
  appearance: none;
  outline: 0;
  box-shadow: none;
  border: 0 !important;
  background-image: none;
}

.filter-todo {
  background-color: #457b9d;
  width: 12rem;
  margin: 1rem;
  padding: 1rem;
  font-size: 1.2rem;
  color: #f1faee;
  cursor: pointer;
}
```
