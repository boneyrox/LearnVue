
# Vue 2.6 App File Structure and Naming Conventions

When you create a new Vue.js 2.6 application using Vue CLI, it sets up a default project structure for you. Here's a breakdown:

## File Structure:

```
my-vue-app/
|-- node_modules/
|-- public/
|   |-- favicon.ico
|   |-- index.html
|-- src/
|   |-- assets/
|   |   |-- logo.png
|   |-- components/
|   |   |-- HelloWorld.vue
|   |-- App.vue
|   |-- main.js
|-- .gitignore
|-- babel.config.js
|-- package.json
|-- README.md
```

## Explanation:

1. **node_modules/**: Contains all the npm packages (dependencies) your project uses.
2. **public/**: Contains static assets.
   - **favicon.ico**: Default favicon.
   - **index.html**: Main HTML file. Vue injects the compiled app here.
3. **src/**: Source code of your application.
   - **assets/**: Directory for assets like images.
   - **components/**: Directory for Vue components. Default: `HelloWorld.vue`.
   - **App.vue**: Root Vue component.
   - **main.js**: Entry point for your app.
4. **.gitignore**: Lists files/directories ignored by Git.
5. **babel.config.js**: Configuration for Babel, a JavaScript compiler.
6. **package.json**: Contains metadata and lists dependencies.
7. **README.md**: Information about the project.

## Naming Conventions:

1. **Directories**: Typically lowercase. E.g., `assets`, `components`.
2. **Vue Files**: PascalCase. E.g., `HelloWorld.vue`, `UserProfile.vue`.
3. **JavaScript Files**: camelCase. E.g., `main.js`, `userProfile.js`.
4. **Asset Files**: Lowercase, sometimes with hyphens. E.g., `logo.png`, `user-avatar.jpg`.
5. **Config and Metadata Files**: Lowercase. E.g., `.gitignore`, `babel.config.js`, `package.json`.

