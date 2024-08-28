# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link
  href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&family=Roboto:wght@400;700&family=Saira+Stencil+One&display=swap"
  rel="stylesheet">
```

Ionicon

``` html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
```

---

## Colors

``` css
--primary-blue: #1589EE;
--secondary-blue: #0070D2;
--dark-blue: #032D60;
--light-blue: #E3F3FF;
--white: #FFFFFF;
--light-gray: #F3F3F3;
--dark-gray: #3E3E3C;
```

## Typography

``` css
--ff-saira-stencil-one: "Saira Stencil One", sans-serif; 
  --ff-poppins: 'Poppins', sans-serif;
  --ff-roboto: 'Roboto', sans-serif;
  --fs-1: 2rem;
  --fs-2: calc(1.813rem + 1vw);
  --fs-3: calc(1.313rem + 1vw);
  --fs-4: 1.4rem;
  --fs-5: 1rem;
  --fs-6: 0.813rem;
  --fs-7: 0.75rem;
  --fw-400: 400;
  --fw-700: 700;
```

## Transition

``` css
--transition-1: 0.25s ease-in-out;
```

## Spacing

``` css
--section-padding: 80px;
```

## Border radius

``` css
--radius-4: 4px;
--radius-12: 12px;
```

---

## Theme Variables

### Dark Mode

``` css
--bg-primary: var(--dark-blue);
  --bg-secondary: var(--secondary-blue);
  --color-primary: var(--white);
  --color-secondary: var(--light-blue);
  --card-shadow: hsla(0, 0%, 0%, 0.4);
  --input-bg: var(--dark-gray);
  --shadow-1: 10px 10px 40px var(--card-shadow);
```

### Light Mode

``` css
 --bg-primary-light: var(--light-blue);
  --bg-secondary-light: var(--white);
  --color-primary-light: var(--dark-blue);
  --color-secondary-light: var(--secondary-blue);
  --card-shadow-light: hsla(0, 0%, 0%, 0.1);
  --input-bg-light: var(--light-gray);
  --shadow-1-light: 10px 10px 40px var(--card-shadow-light);
```
