# Tailwind Clipboard Landing Page - In work ...

![cover](./assets/)


## 🦉 Main Information

This is a landing page for an app called Clipboard.

Includes:
- top hero part with a background image which is a separate image for mobile version
- logo with butoons to download the app
- part with some text and images
- part with some items with icons and part with some logos using Flexbox
- footer part

This page a responsive for all devices. Built with Html and style with Tailwind CSS. 

The project was created according to the Brad Traversy "Tailwind CSS From Scratch" course.

## 🦊 Usage

Copy 'tailwind-simple-starter' and rename it.

Make a screen sizes, color and font configurations in 'tailwind.config.js' and then run it 

```
module.exports = {
  content: ['./*.html'],
  theme: {
    screens: {
      sm: '480px',
      md: '768px',
      lg: '976px',
      xl: '1440px',
    },
    extend: {
      colors: {
        strongCyan: 'hsl(171, 66%, 44%)',
        lightBlue: 'hsl(233, 100%, 69%)',
        darkGrayishBlue: 'hsl(210, 10%, 33%)',
        grayishBlue: 'hsl(201, 11%, 66%)',
      },
      fontFamily: {
        sans: ['Bai Jamjuree', 'sans-serif'],
      },
    },
  },
  plugins: [],
}
```

```
npm run watch
```

