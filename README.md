# ABOUT THE PROJECT

This is a small project to continue learning about state and animations.
We can find two Files in the App.jsx file. One in which the carousel style is made from scratch.

## ABOUT CAROUSEL.JSX

This component was done by creating two states.
One to load the list of people, and the other to control the current person.

To animate it, useEffect was also implemented with its own setInterval and ClearInterval functions.

Clicking the buttons will load the next slide and previous slide.

It also has a auto-play feature in which the useEffect mentioned above is used.

## ABOUT THE SLICK CAROUSEL

In this component we utilize the react-slick and slick-carousel libraries.

This makes the whole first component in a much simpler way.

We load the data and create the component.

After it is important to create the settings that the slider is going to use.

```js
const settings = {
  dots: true,
  infinite: true,
  autoplay: true,
  speed: 500,
  autoplaySpeed: 2000,
  slidesToShow: 1,
  slidesToScroll: 1,
  pauseOnHover: true,
};
```

After we must add the Slider that is given with the import we made. This cover the complete list of items that will be added to the slider.
