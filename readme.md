# Ebook Website

Bootstrap website for downloading a free E-book. This website has a light, business-like design.

<img src="./images/screen.png"  />

![image](https://github.com/user-attachments/assets/c8c4c86c-ef59-48a1-9685-8936aedd4d0f)

![image](https://github.com/user-attachments/assets/ae2eb2f5-cadc-48c8-9c22-8e45cad8ad90)

![image](https://github.com/user-attachments/assets/d23b510a-da42-437e-be4b-f0381ef75439)

![image](https://github.com/user-attachments/assets/afe64f56-e114-4ecd-bbd4-ac88c9a17a2d)


## Features

- Modern layout with custom colors/styles/backgrounds
- Responsive design
- Sticky navbar with style changes on scroll
- Bootstrap modals
- Form & input styles
- Testimonials
- Contact page with Google Map

## Usage

This website is built with [Bootstrap](https://getbootstrap.com/) and [Sass](https://sass-lang.com/). It uses [Font Awesome](https://fontawesome.com/) for icons.

In order to customize this website, you need to install [Node.js](https://nodejs.org/en/). Then, clone this repository and run:

```bash
npm install
```

This will install Bootstrap, Sass and Font Awesome. To build your CSS files from Sass, run:

```bash
npm run sass:build
```

To watch your Sass files for changes, run:

```bash
npm run sass:watch
```

You can add Bootstrap variables to the `bootstrap.scss` file. You can look at the file `node_modules/bootstrap/dist/scss/_variables.scss` for a list of all the variables. Do NOT edit the `variables.scss` file directly, as it will be overwritten when you update Bootstrap.

To add your own custom styles, use the `styles.scss` file.
