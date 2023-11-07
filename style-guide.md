# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Very Dark Magenta: hsl(300, 43%, 22%)
Soft Pink: hsl(333, 80%, 67%)

### Neutral

Dark Grayish Magenta: hsl(303, 10%, 53%)
Light Grayish Magenta: hsl(300, 24%, 96%)
White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [League Spartan](https://fonts.google.com/specimen/League+Spartan)
- Weights: 400, 500, 700


<!-- star -->
.rating {
    display: flex;
    justify-content: center;
    align-items: center;
    direction: rtl;
    
}
.rating input {
    display: none;
}
.rating label {
    display: inline-block;
    width: 2em;
    
}
.rating label:hover,
.rating label:hover ~ label,
.rating input:checked ~ label {
  color: orange;
}

<!-- html  -->

<div class="rating">
      <input type="radio" name="rating" id="rating-1" value="1" />
      <label for="rating-1"> ★ <!--  <img src="/images/icon-star.svg" alt="a star"> --> </label> 
      <input type="radio" name="rating" id="rating-2" value="2" />
      <label for="rating-2"> ★ <!-- <img src="/images/icon-star.svg" alt="a star"> --> </label>
      <input type="radio" name="rating" id="rating-3" value="3" />
      <label for="rating-3"> ★ <!-- <img src="/images/icon-star.svg" alt="a star"> --> </label>
      <input type="radio" name="rating" id="rating-4" value="4" />
      <label for="rating-4"> ★ <!-- <img src="/images/icon-star.svg" alt="a star"> --> </label>
      <input type="radio" name="rating" id="rating-5" value="5" />
      <label for="rating-5"> ★ <!-- <img src="/images/icon-star.svg" alt="a star"> --> </label>
    </div>