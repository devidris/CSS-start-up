# CSS-start-up
My CSS start up code


```css
/* You can add global styles to this file, and also import other style files */
@import url("https://fonts.googleapis.com/css2?family=Irish+Grover&family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;0,900;1,400;1,500;1,600;1,700;1,800;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

:root {
  --grey-0-0: #000000;
  --grey-0-1: #080808;
  --grey-0-2: #101010;
  --grey-0-3: #181818;
  --grey-0-4: #202020;
  --grey-0-5: #282828;
  --grey-0-6: #303030;
  --grey-0-7: #383838;
  --grey-0-8: #404040;
  --grey-0-9: #484848;
  --grey-1-0: #505050;
  --grey-1-1: #585858;
  --grey-1-2: #606060;
  --grey-1-3: #686868;
  --grey-1-4: #696969;
  --grey-1-5: #707070;
  --grey-1-6: #787878;
  --grey-1-7: #808080;
  --grey-1-8: #888888;
  --grey-1-9: #909090;
  --grey-2-0: #989898;
  --grey-2-1: #a0a0a0;
  --grey-2-2: #a8a8a8;
  --grey-2-3: #a9a9a9;
  --grey-2-4: #b0b0b0;
  --grey-2-5: #b8b8b8;
  --grey-2-6: #bebebe;
  --grey-2-7: #c0c0c0;
  --grey-2-8: #c8c8c8;
  --grey-2-9: #d0d0d0;
  --grey-3-0: #d3d3d3;
  --grey-3-1: #d8d8d8;
  --grey-3-2: #dcdcdc;
  --grey-3-3: #e0e0e0;
  --grey-3-4: #e8e8e8;
  --grey-3-5: #f0f0f0;
  --grey-3-6: #f5f5f5;
  --grey-3-7: #f8f8f8;
  --grey-3-8: #ffffff;
}

* {
  margin: 0;
  padding: 0;
}
*,
*::before,
*::after {
  box-sizing: inherit;
}

html {
  box-sizing: border-box;
  font-size: 62.5%; /* 1rem = 10px, 10px/16px = 62.5% */

  /* @media only screen and (max-width: 64em) {
     font-size: 50%;
  } */
}

body {
  font-family: "Poppins", sans-serif;

  font-weight: 400;
  line-height: 1.6;
  color: var(--grey-3-8);
  /* background-image: linear-gradient(to right bottom, red, blue);
     background-size: cover;
     background-repeat: no-repeat; */
}

a {
  text-decoration: none;
  color: var(--grey-0-0);
}
/*
  ::selection {
    background-color: #07091d;
    color: #fff;
  } */

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Playfair Display", serif;
  margin-bottom: 0;
}

p {
  font-family: "Poppins", sans-serif;
}

body {
  margin: 0;
  font-family: Roboto, "Helvetica Neue", sans-serif;
}
