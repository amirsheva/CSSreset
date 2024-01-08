# CSSreset


/*
* Reset CSS
* Version 1.0
* By Amir Khakdoust
* Copyright 2024 ManiaWebGroup
* License: MIT
*/

/* Box-sizing reset */
*, *::before, *::after {
    box-sizing: border-box;
}

/* Margin and padding reset */
* {
    margin: 0;
    padding: 0;
}

/* List-style reset */
ul[role='list'], ol[role='list'] {
    list-style: none;
}

/* Smooth scroll behavior */
html:focus-within {
    scroll-behavior: smooth;
}

/* Link underline skip for links without class */
a:not([class]) {
    text-decoration-skip-ink: auto;
}

/* Responsive media */
img, picture, svg, video, canvas {
    max-width: 100%;
    height: auto;
    vertical-align: middle;
    font-style: italic;
    background-repeat: no-repeat;
    background-size: cover;
}

/* Inherit font for form elements */
input, button, textarea, select {
    font: inherit;
}

/* Reduced motion media query */
@media (prefers-reduced-motion: reduce) {
    html:focus-within,
    *,
    *::before,
    *::after {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
        scroll-behavior: auto !important;
        transition: none;
    }
}

/* Body and html full height */
body, html {
    height: 100%;
    scroll-behavior: smooth;
}

/* End of Reset CSS */
