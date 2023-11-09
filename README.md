## How to use this Boilerplate.

1. Clone this repository.

```bash
git clone git@github.com:CollectionOP/Tailwind-Boilerplate.git
```

2. Remove the .git directory to add your own repository.

```bash
rm -rf .git
```

3. Install devDependency.

```bash
npm install
```

4. To use the Tailwind CLI build process run.

```bash
npm run watch
```

<br>

## Create your own Tailwind Project.

#### In your own project folder run these commands.

1. Run in terminal.

```bash
npm init -y
```

2. Run in terminal.

```bash
npm install -D tailwindcss
npx tailwindcss init
```

3. Replace in tailwind.config.js

```js
content: ["./src/**/*.{html,js}", "./*"],
```

4. Create a `src` folder with a `css`/style.css and `js`/index.js

5. Add in your `css`/style.css

```CSS
@tailwind base;
@tailwind components;
@tailwind utilities;
```

6. Run in terminal.

```bash
npx tailwindcss -i ./src/css/style.css -o ./dist/style.css --watch
```

7. Create a index.html

8. Start using Tailwind in your HTML

```HTML
<link rel="stylesheet" href="dist/style.css">
```

9. Create a .gitignore file and add

```bash
.DS_store # optional
node_modules
```

## Learn More

You can learn more in the [Tailwind CLI Documentation](https://tailwindcss.com/docs/installation)
