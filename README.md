tasks-typescript-app

A simple Task Management application built with React and TypeScript, following the Practical TypeScript – Course for Beginners (freeCodeCamp) tutorial.
This project demonstrates how to use TypeScript in a React environment, including typed props, state, events, and drag-and-drop.

🚀 Features

Add and delete tasks

Mark tasks as complete or move back to active

Drag-and-drop tasks between active and completed lists (react-beautiful-dnd)

Fully typed components, props, events, and hooks for better maintainability

🛠 Tech Stack

React (with JSX in .tsx files)

TypeScript

react-beautiful-dnd

CSS Modules / custom styling

Vite (or CRA depending on setup)


📖 TypeScript Concepts Used

Interfaces for props and data models (Task type)

Typed Hooks: useState<Task[]>, useRef<HTMLInputElement>

Event Typing: React.FormEvent, React.ChangeEvent

Function Prop Typing for callbacks

useReducer with typed actions (if implemented)

Strict null checks with optional chaining

📦 Installation & Setup

Clone the repository:

git clone https://github.com/EphrataTech/tasks-typescript-app.git
cd tasks-typescript-app


Install dependencies:

npm install


Start development server:

npm run dev

🎯 How It Works

Adding a Task — User enters text and submits form → task is typed as { id: number, text: string, isDone: boolean } and added to tasks state.

Moving Tasks — Dragging between lists updates the isDone property.

Deleting Tasks — Removes the selected task from the array.

Type Safety — Every prop, state, and event handler is strongly typed to prevent runtime errors.


📚 Learning Outcomes

By building this app, you will:

Understand how to type props, events, hooks, and components in React.

Learn to use TypeScript to catch errors before runtime.

Apply drag-and-drop functionality with strong typing.


