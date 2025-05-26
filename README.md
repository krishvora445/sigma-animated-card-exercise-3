# Sigma Web Development - Exercise 3: Advanced Animated Cards

This repository showcases my solution for Exercise 3 of the Sigma Web Development course. The project is a modern, responsive card UI component built with HTML and advanced CSS, featuring multiple animations and interactive effects.

![Demonstration of the animated cards](demo.gif)

---

## 🚀 Project Features

This project goes beyond basic styling and incorporates several modern CSS techniques to create a dynamic and engaging user experience.

- Staggered On-Load Animation: Cards fade and slide into view sequentially using `@keyframes` and `animation-delay`.
- Advanced Hover Effects:
  - The card lifts and grows, with a more dynamic shadow.
  - The main image smoothly zooms in.
  - A "Read More" button elegantly slides up and fades in, providing a clean initial view.
- Gradient Text Heading: A stylish linear-gradient is applied to the main title using `background-clip`.
- Interactive Feedback: The button provides instant tactile feedback by shrinking slightly when clicked (`:active` state).
- Responsive Design:** The layout uses Flexbox with `flex-wrap` to ensure the cards adapt gracefully to different screen sizes.

## 🛠️ Key CSS Techniques Used

- CSS Animations (`@keyframes`)
- CSS Transforms (`translate`, `scale`)
- CSS Transitions with `cubic-bezier` timing functions
- Advanced Selectors (`:nth-child()`, `:hover`, `:active`)
- Flexbox for layout and alignment (`flex-grow`, `gap`)
- `object-fit` for uniform image handling
- `background-clip: text` for gradient text effects

## 🙏 Acknowledgements

- This exercise is part of the amazing Sigma Web Development Course by CodeWithHarry.
