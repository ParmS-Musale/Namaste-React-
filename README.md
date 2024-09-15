
# Namaste React - Day 1 🚀

## Introduction to React

React is a powerful JavaScript library for building user interfaces, developed by Facebook. It excels at creating fast and interactive web applications, particularly single-page applications.

## Key Concepts 

### 1. What is a CDN (Content Delivery Network)?

A **CDN (Content Delivery Network)** is a system of distributed servers that deliver web content to a user based on their geographic location. CDNs help improve the performance, speed, and reliability of a website by reducing the distance between the server and the user.

- **How it works:**
  - When a user requests a web page, the CDN delivers the content from the server closest to the user, reducing load times and latency.
  - CDNs are widely used to deliver assets like images, videos, stylesheets, and scripts.

- **Example:**
  - React and other libraries can be delivered via CDN, allowing you to quickly include them in your projects without needing to install them locally.

### 2. What does "cross-origin" mean?

**Cross-Origin** refers to when a web page or resource is accessed from a different domain, protocol, or port than the one currently being used. This is common in web development when resources like images, fonts, or APIs are hosted on different domains.

- **Same-Origin Policy:**
  - Browsers enforce a security measure called the "Same-Origin Policy," which restricts how resources on one origin can interact with resources from another origin to prevent malicious attacks.

- **Cross-Origin Resource Sharing (CORS):**
  - CORS is a mechanism that allows servers to specify who can access their resources from different origins. It is implemented via HTTP headers.

- **Example:**
  ```html
  <script src="https://example.com/some-script.js" crossorigin></script>
  
# Namaste React - Day 2 🚀

## 1. What is Cross-Origin?

**Answer**: Cross-origin refers to making requests from one domain to another different domain. For example, if a web application on `example.com` requests data from `api.example.org`, it's a cross-origin request. 

---

## 2. What is `npm` at a Basic Level?

**Answer**: `npm` (Node Package Manager) is a tool used for managing packages (libraries and modules) in Node.js projects. It allows you to install, update, and manage dependencies for your project and access a large registry of open-source packages.

---

## 3. What is `package.json`?

**Answer**: `package.json` is a file in Node.js projects that contains metadata about the project, including its name, version, dependencies, and scripts. It helps manage project dependencies and configurations.

---

## 4. What is Babel in Short and Easy to Understand?

**Answer**: Babel is a JavaScript compiler that converts modern JavaScript code into an older version that is compatible with older browsers. It allows developers to use the latest JavaScript features while ensuring compatibility across different browsers.

---

## 5. What is a Bundler?

**Answer**: A bundler is a tool that combines multiple files (such as JavaScript, CSS, and HTML) into a single or a few bundles. This process helps optimize the loading of resources by reducing the number of HTTP requests and managing dependencies.

---

## 6. What is `npx`?

**Answer**: `npx` is a command-line tool that comes with npm, allowing you to run Node.js packages and commands without installing them globally. It is useful for executing commands and running packages on-the-fly.

---

## 7. What Does `-D` Mean in `npm install -D parcel`?

**Answer**: In `npm install -D parcel`, `-D` stands for `--save-dev`, indicating that the package should be installed as a development dependency, used only in the development phase of the project.

---

## 8. What is `package-lock.json`?

**Answer**: `package-lock.json` is an auto-generated file that locks the exact versions of dependencies installed in a project. It ensures consistent installations across different environments by recording the full dependency tree.

---

## 9. What is a Transitive Dependency?

**Answer**: A transitive dependency is a dependency of a dependency. If your project depends on `Library B`, and `Library B` depends on `Library C`, then `Library C` is a transitive dependency for your project.

---
# Namaste React - Day 3 🚀

## 1. What is the Difference Between React Elements and Components?

### **React Elements**
- **Definition**: React elements are the basic building blocks of a React application. They describe what should appear on the screen and are immutable.
- **Characteristics**: Simple units of UI, created using JSX or `React.createElement()`. They don't have internal logic or state.

### **React Components**
- **Definition**: React components are reusable pieces of UI that can be composed together to build more complex UIs. They can be functional or class-based.
- **Characteristics**: Components can manage state, accept props, and contain logic. They can return React elements and can be composed into other components.

## 2. What is Component Composition?

### **Definition**
- **Concept**: Component composition is the practice of combining multiple React components to build more complex UIs. It involves using components as building blocks to create a complete UI layout.
- **Benefits**: Enhances modularity and reusability, allowing for cleaner and more maintainable code. It helps in breaking down complex UIs into simpler, manageable parts.

## 3. How to Correct Common Syntax Errors in Functional Components?

### **Common Errors and Corrections**
- **Error**: Using incorrect syntax for returning JSX, such as mixing `return` statements with parentheses.
- **Correction**: Ensure that the JSX returned from a functional component is enclosed correctly within parentheses without the `return` keyword if using implicit returns. For explicit returns, use the `return` keyword properly.

## 4. What is JSX and How is it Used?

### **Definition**
- **JSX**: JSX stands for JavaScript XML. It is a syntax extension for JavaScript that allows writing HTML-like code within JavaScript files. It makes it easier to describe what the UI should look like.
- **Usage**: JSX is compiled by tools like Babel into `React.createElement()` calls, which create React elements that are used to render the UI. It provides a more readable and expressive way to create elements compared to plain JavaScript.

# Namaste React - Day 4 🚀

## 1. Cloudinary
- **Definition**: Cloudinary is a cloud-based service for managing images and videos, providing features like optimization, transformation, and delivery.
- **Common Error**: `404 (Not Found)` indicates the requested image or resource could not be found. This often means the URL is incorrect or the resource has been deleted.

## 2. Carousel
- **Definition**: A carousel is a component that allows users to cycle through a series of items, typically images or content, in a slideshow format. It’s used to display multiple pieces of content in a confined space with navigation controls.

## 3. Props
- **Definition**: Props (short for properties) are used to pass data from a parent component to a child component in React. They allow components to be dynamic and reusable by providing them with different inputs.

## 4. Cuisine
- **Definition**: Cuisine refers to a style or method of cooking, especially as characteristic of a particular country, region, or establishment. For example, Italian cuisine includes dishes like pasta and pizza.

## 5. Conflict-Driven UI
- **Definition**: Conflict-driven UI refers to designing user interfaces that handle and resolve conflicts in data or user actions effectively. It involves ensuring that the UI provides clear feedback and resolution paths when conflicting actions or states arise.

# Namaste React - Day 5 🚀

## 1. Importance of the `src` folder
- The `src` folder contains the source code of the application.
- It organizes components, utilities, styles, and logic, making it easier to manage.

## 2. Types of Exports in JavaScript
- **Named Export**: Allows exporting multiple things from a module.
  - Example: `export const myVar = 42;`
- **Default Export**: Only one default export is allowed per module.
  - Example: `export default function() {...}`

## 3. Can We Use Default Export with Named Export?
- Yes, we can combine both in the same module.
  - Example:
    ```js
    export const myVar = 42;
    export default function() {...}
    ```

## 4. What are React Hooks?
- Hooks are functions that let you use state and lifecycle features in functional components.
- Common Hooks:
  - `useState`: For state management.
  - `useEffect`: For side effects like fetching data.
  
## 5. What is the Virtual DOM?
- A lightweight copy of the actual DOM, maintained in memory.
- React updates the Virtual DOM first, compares it with the real DOM, and only updates the necessary parts, improving performance.

## 6. Types of Algorithms in React
- **Diffing Algorithm**: React’s algorithm for comparing changes in the Virtual DOM with the actual DOM.
  
## 7. Reconciliation in React
- The process where React updates the actual DOM based on changes detected in the Virtual DOM using the diffing algorithm.

## 8. What is React Fiber?
- A new reconciliation engine in React 16+.
- Improves performance by breaking down the rendering process into units of work and prioritizing tasks.

# Namaste React - Day 6 🚀
#### 1. What is Shimmer?
Shimmer is a placeholder UI component used to indicate loading states. It typically displays a skeleton or shimmer effect to mimic the layout of the content that will be loaded, improving user experience by giving a visual cue that data is being fetched.

# Namaste React - Day 7 🚀

1. **React Router DOM**:
   - **Why use React Router DOM?**  
     React Router DOM allows you to implement dynamic routing in a web app, which helps in rendering different components or pages based on the URL.
   
   - **createBrowserRouter**:
     - A method in `react-router-dom` used to create the browser's routing system. It handles navigation via the URL.
   
   - **RouterProvider**:
     - This component is used to wrap your app and provide the router configuration to all child components.

   - **useParams**:
     - Hook that lets you extract dynamic parameters from the URL, such as an `id` of a restaurant or user.

   - **useRouterError**:
     - Provides error handling for routes that don't match any defined paths, enabling error boundary display.
     - 
     # Namaste React - Day 8 🚀

1. **Class-Based Components:**
   - In React, class components extend `React.Component`.
   - They have lifecycle methods such as `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`.
   - Use a constructor to initialize the state using `this.state`.

2. **State in Class Components:**
   - State is defined as an object, and updates to state are done using `this.setState()`.
   - Example:
     ```js
     this.state = { key: value };
     this.setState({ key: newValue });
     ```

3. **Props in Class Components:**
   - Props are passed to the component and accessed via `this.props`.
   - Props are read-only, used to display dynamic data.

4. **Lifecycle Methods:**
   - `componentDidMount()`: Executed after the component is rendered for the first time. Used for side effects such as API calls.
   - `componentDidUpdate()`: Runs after the component updates.
   - `componentWillUnmount()`: Cleanup actions like clearing timers or subscriptions.

5. **Fetching Data with Lifecycle Methods:**
- API calls are made inside `componentDidMount()`.
- Data can be stored in the state and rendered on the UI.

6. **Handling Component Updates:**
-Lifecycle methods handle the process of fetching, updating, and displaying data.
- React efficiently manages DOM updates when state changes.
