# E-Shop


## Project description

Simple online store built using `React's functional components`, no link to the backend yet (but I'm going to learn backend frameworks and make a backend for this project over the holidays).

The original intention of this project is to create competition in the Kazakhstan market, create more online stores similar to Kaspi stores, and realize the networking of all people and online shopping.

New React high-level component concepts such as `function components`, `Hook`, `routing`, `useState`, and `useMemo` are used throughout the process.

In the project, each page is in the `pages` directory, and static data is in the `data` directory
`Layout` in the components directory is the entire layout template, and `Product` is the item component

The `layout` template is the part of the page that has been redirected but remains unchanged: such as the navigation bar, sidebar, and background board. The paths of these things have changed, and they will not change, so they are extracted into the `Layout` component

The `Product component` : each item, regardless of computer, mobile phone, etc., has the same data format, then we can abstract a data display method, which is the function of this component.

`util` is toolkit, where some commonly used tool functions are placed.

### result screen

**home page**

![home_page](/result_screen/home_page.jpg)

**mobile page**

![mobile page](/result_screen/mobile_screen.jpg)

**login page**

![login page](/result_screen/login_page.jpg)

### install & run

download dependencies

- `npm install`

run local server

- `npm run dev`

### technology stack

- `React 17.0.2`

- `Vite` scaffold

- `CSS Module`


### about Author
- Tokmukamet Bayashat
- github: https://github.com/Bayashat/
- instagram: bayashat_t


