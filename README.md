Vue 3 Todo App with Vuex 4 and TypeScript
=========================================

This is a **Todo application** built with **Vue.js 3**, **Vuex 4**, and **TypeScript**. The app allows users to add, display, edit, and delete todo items. It demonstrates best practices for structuring a Vue.js application using the Composition API, Vuex modules with TypeScript support, and follows good programming practices.

Features
--------

-   **Add Todos**: Users can add new todo items.
-   **Display Todos**: All todos are displayed in a list.
-   **Edit Todos**: Double-click on a todo to edit its text.
-   **Toggle Completion**: Mark todos as completed or pending.
-   **Delete Todos**: Remove todos from the list.
-   **State Management**: Uses Vuex 4 for state management with TypeScript typings.
-   **Composition API**: Implements components using Vue 3's Composition API.
-   **TypeScript Support**: Full TypeScript support for type safety and better development experience.

* * * * *

Getting Started
---------------

### Installation

1.  **Clone the Repository**
    
        git clone https://github.com/GeorgeOkarskyi/vue-to-do-list.git

2.  **Install Dependencies**

        npm install

### Running the Application

**Development Server**

Start the development server:

    npm run dev

This will start the app at `http://localhost:5173` (or a similar port). Open this URL in your browser to view the app.

**Build for Production**

To build the app for production:

    npm run build

The built files will be in the `dist` directory.

* * * * *

Project Structure
-----------------

    vue-to-do-list/
    ├── public/
    ├── src/
    │   ├── assets/
    │   ├── components/
    │   │   ├── TodoInput.vue
    │   │   ├── TodoItem.vue
    │   │   └── TodoList.vue
    │   ├── store/
    │   │   ├── index.ts
    │   │   └── modules/
    │   │       └── todos.ts
    │   ├── types/
    │   │   ├── store.ts
    │   │   └── todo.ts
    │   ├── App.vue
    │   ├── main.ts
    │   ├── style.css
    │   └── vite-env.d.ts

**Key Directories and Files:**

-   **src/components/**: Vue components (`TodoInput.vue`, `TodoItem.vue`, `TodoList.vue`).
-   **src/store/**: Vuex store configuration and modules.
-   **src/types/**: TypeScript interfaces and type definitions.
-   **src/main.ts**: Entry point of the application.
-   **src/App.vue**: Root Vue component.

* * * * *

Technologies Used
-----------------

-   **Vue.js 3**: JavaScript framework for building user interfaces.
-   **Vuex 4**: State management library for Vue.js applications.
-   **TypeScript**: Typed superset of JavaScript that compiles to plain JavaScript.
-   **Vite**: Next-generation frontend tooling for fast development.
-   **Composition API**: Modern way to compose component logic in Vue.js 3.
-   **CSS**: Styling components.

* * * * *