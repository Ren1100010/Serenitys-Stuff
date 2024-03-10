# Portfolio Website V2
This is a template for building a portfolio website using HTML, CSS, and Javascript. It also uses the CSS framework [Tailwind CSS](https://tailwindcss.com/) to make styling your website easier.

## Installation
Upon creating a fork of the template and viewing the folder in Visual Studio Code, install dependencies in your terminal:
```
npm install
```

## Editing the Template
### Previewing
To enter "watch" mode (where all of your changes are saved and updated), run
```
npm start
```
This also creates a server where you can view your changes in real time.

For one-time builds, run `npm run build`.

### Content editing
Edit the contents of the website by changing the content in `index.html`. You can use the custom classes and colors from [the website](https://tailwindcss.com/docs/installation) in your HTML elements, for example:
```html
<div class="text-rose-600 text-2xl bg-neutral-50">
  Hello, world!
</div>
```
will create a box with large red text and a white background.

Most of the CSS you will need to know to make your portfolio will be available in TailwindCSS, but for custom or additional styles you can create `.css` files in the `src` directory and `<link>` them in your main HTML file. Alternatively, you can also edit the `styles.css` file. You should place your custom styles **after** the Tailwind declaration:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;

/* place custom styles here */
```

## Resources and Documentation for creating your website
- [TailwindCSS Documentation](https://tailwindcss.com/docs/installation)
- W3Schools [HTML](https://www.w3schools.com/html/) and [CSS](https://www.w3schools.com/css/default.asp) References
- [Codecademy Web Development Courses](https://www.codecademy.com/catalog/subject/web-development)