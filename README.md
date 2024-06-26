# LMS Frontend

### Setup instruction

1. Clone the project

```
  git clone  https://github.com/Diveshkedisingh/lms-frontend-hn.git
```

2. Move into the directory

```
cd lms-frontend-hn
```

3. install dependencies
```
 npm install
```

4. run the server
```
npm run dev
```

### Setup instruction for tailwind

[tail wind official instruction doc](https://tailwindcss.com/docs/installation)

1. Install tailwindcss
```
npm install -D tailwindcss
```
2.Create tailwind config file
```
npx tailwindcss init
```

3. Add file extensions to tailwind config file in the content property
```
 "./src/**/*.{html,js,jsx,ts,tsx}"
```

4. add the tailwind directives at the top of the index.css file
```
@tailwind base;
@tailwind components;
@tailwind utilities;

```

5. Adding plugins and dependencies
```
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp

```
### configure auto import sort esline
1.install simple import sore
```
  npm i -D eslint-plugin-simple-import-sort

```

2. Add rule in `.eslint.cjs`
``
 'simple-import-sort/imports': "error"
```

3. add simple-import sort plugin in `.eslint.cjs`
```
plugins: ['react-refresh', 'simple-import-sort']

```
4. to enable auto import sort on file save in vscode
    
    -open `setting.json`
    -add the following config

```
  "editor.codeActionOnSave":{
    "source.fixAll.eslint": true
  }

```

### import toaster
