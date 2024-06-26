#### Attribution

Original code by [Amelia Wattenberger](https://github.com/Wattenberger/Wattenberger-2019)

#### Instructions

Install dependencies

```bash
npm i
```

To start the project locally

```bash
npm start
```

To deploy to production run the command below. It will generate a `build` folder in your root directory

```bash
npm run build
```

### Deployment

You can deploy the website to Netlity in two ways:

1. Drag and drop method following this [tutorial](https://www.freecodecamp.org/news/how-to-deploy-a-react-application-to-netlify-363b8a98a985/)

2. [Continuous Deployment](https://docs.netlify.com/configure-builds/get-started/)

### Editing the home page

You can edit the text on the home page on the [`HomeHeader.jsx`](src/components/Home/HomeHeader/HomeHeader.jsx)

### Gotchas

- If you see this error on your Mac terminal

```bash
  gyp: No Xcode or CLT version
```

Fix: run this code in your terminal

```bash
sudo xcode-select --reset
```
