# Box Animation Design

A stylish and smooth box animation design created using HTML and CSS. This animation can be applied to buttons, cards, modals, or interactive UI elements.
##Demo Screenshort
![box-animation](https://github.com/Dirojini/box-animation/blob/1e3b5a0ea29399cf2b33c1397ee2f1d3ac3acf48/Screenshot%202024-12-24%20114343.png)
## Features

- **Smooth Scaling and Translation**: Boxes animate with fluid scaling and movement.
- **Customizable Speed**: Adjust the duration and timing functions with ease.
- **Responsive Design**: Animation adapts to various screen sizes.
- **Reusable**: Modular CSS allows easy reuse and integration into different projects.

## Technologies Used

- **HTML** – For the structure of the animated box.
- **CSS** – For the animation and visual styling.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Dirojini/box-animation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd box-animation
   ```
3. Open the `index.html` file in your web browser.

## File Structure

```
box-animation/
│
├── index.html       # Main HTML file
└── box.css          # CSS for box animation
```

## Sample Box Animation (box.css)

```css
.box {
  width: 100px;
  height: 100px;
  background-color: #4caf50;
  transition: transform 0.5s ease, box-shadow 0.5s ease;
}

.box:hover {
  transform: scale(1.2) translateY(-10px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}
```




## Future Enhancements

- **Bounce and Elastic Effects**
- **Color Transition on Hover**
- **JavaScript Triggered Animations**
- **Multiple Box Animations**

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

