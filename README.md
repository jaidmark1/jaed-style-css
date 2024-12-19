# jaed-style-css/* Reset margin and padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Background image for the entire page */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: url(bbbb.jpg) no-repeat center center fixed;
    background-size: cover;
}

/* Header styling */
header {
    background: rgba(251, 251, 251, 0.674); /* Semi-transparent background for contrast */
    color: #000000;
    padding: 20px;
    text-align: center;
}

/* Navigation styling */
nav {
    background: rgba(0, 0, 0, 0.8); /* Darker background for the navigation */
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Main content styling */
main {
    padding: 20px;
    background: rgba(255, 255, 255, 0.8); /* Light background with some transparency */
    border-radius: 8px; /* Rounded corners */
    max-width: 1200px;
    margin: auto;
}

/* Section styling */
section {
    margin: 20px 0;
}

/* Footer styling */
footer {
    background: rgba(0, 0, 0, 0.6); /* Semi-transparent background for contrast */
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

/* Links */
a {
    color: #010e1b;
}

a:hover {
    text-decoration: underline;
}

/* Responsive design */
@media (max-width: 600px) {
    nav ul li {
        display: block;
        margin: 10px 0;
    }
}
