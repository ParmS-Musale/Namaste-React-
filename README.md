
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




