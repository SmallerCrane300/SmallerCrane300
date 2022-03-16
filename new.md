/* New Font */

@font-face {
  font-family: sfuidisplay;
  src: url(https://raw.githubusercontent.com/squid-app/desktop/master/src/fonts/SF-UI-Display-Regular.ttf);
}

/* Background Color And Set Font */

body {
  background-color: #2e2e2e;
  font-family: sfuidisplay;
}

/* Nav Bar */

nav.bar {
  overflow: auto;
  width: 100%;
  background-color: #555;
  border-radius: 15px;
  animation-name: swap-bottom;
  animation-duration: 0.75s;
}

/* Nav Bar Link */

nav.bar a {
  padding: 12px;
  display: inline-block;
  color: white;
  text-decoration: transparent;
  float: left;
  animation-name: swap-top;
  animation-duration: 0.75s;
}

nav.bar a:hover {
  padding: 12px;
  color: yellowgreen;
  text-shadow: 0px 0px 8px yellowgreen;
  display: inline-block;
  text-decoration: transparent;
  float: left;
  animation-name: swap-top;
  animation-duration: 0.75s;
} 

nav.bar a.active {
  padding: 12px;
  float: left;
  color: yellowgreen;
  text-shadow: 0px 0px 8px yellowgreen;
  text-decoration: transparent;
  display: inline-block;
  animation-name: swap-top;
  animation-duration: 0.75s;
}

/* Headers */

h1 {
  text-align: center;
  color: white;
  text-shadow: 3px 1px yellowgreen;
  font-size: 45px;
  margin-top: 75px;
  animation-name: swap-right;
  animation-duration: 1.25s;
}

h1.left {
  text-align: left;
  color: white;
  text-shadow: 3px 1px yellowgreen;
  font-size: 45px;
  margin-top: 75px;
  animation-name: swap-right;
  animation-duration: 1.25s;
}

/* Paragraph */

p {
  width: 100%;
  text-align: center;
  color: whitesmoke;
  text-shadow: 2px 1px greenyellow;
  animation-name: swap-right;
  animation-duration: 1.25s;
}

p.left {
  width: 100%;
  text-align: left;
  color: whitesmoke;
  text-shadow: 2px 1px greenyellow;
  animation-name: swap-right;
  animation-duration: 1.25s;
}

/* Profile Image */

img.profile {
  border-width: 5px;
  border-color: blueviolet;
  border-style: solid;
  border-radius: 50%;
  width: 100px;
  height: 100px;
  margin-left: auto;
  margin-right: auto;
  display: block;
  box-shadow: 0px 0px 20px blueviolet;
  animation-name: imgpopout;
  animation-duration: 2.25s;
}

/* Game Link */

a.game {
  color: white;
  border-radius: 15px;
  background-color: #555;
  text-decoration: transparent;
  margin-right: 1%;
  margin-top: 1%;
  display: inline-block;
  padding: 16px;
  animation-name: fadein;
  animation-duration: 0.75s;
}

a.game:hover {
  background-color: #666;
  box-shadow: 0px 0px 8px greenyellow;
}

/* Bookmarklet Buttons */

a.bmrklet {
  color: white;
  border-radius: 15px;
  background-color: #555;
  text-decoration: transparent;
  margin-right: 1%;
  margin-top: 1%;
  display: inline-block;
  padding: 16px;
  animation-name: fadein;
  animation-duration: 0.75s;
}

a.bmrklet:hover {}

/* Horizontal Line */

hr {
  border-color: white;
  animation-name: flowout;
  animation-duration: 1.25s;
}

/* Animations */

@keyframes imgpopout {
  0% { width: 0px; height: 0px; }
  100% { width: 100px; height: 100px; } 
}

@keyframes flowout {
  0% { width: 0%; }
  100% { width: 100%; } 
}

@keyframes fadein {
  0% { opacity: 0%; }
  100% { opacity: 100%; }
}

@keyframes swap-bottom {
  0% { transform: translateX(0) translateY(-100%); }
  100% { transform: translateX(0) translateY(0); }
}

@keyframes swap-top {
  0% { transform: translateX(0) translateY(100%); }
  100% { transform: translateX(0) translateY(0); }
}

@keyframes swap-right {
  0% { transform: translateX(-100%) translateY(0); }
  100% { transform: translateX(0) translateY(0); }
}
