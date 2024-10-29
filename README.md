/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #1c1c1c;
    padding: 20px;
}

.header .logo img {
    width: 100px;
}

.navbar a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

.navbar a:hover {
    text-decoration: underline;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 100px;
    background: linear-gradient(to right, #1c1c1c, #2b2b2b);
    color: white;
}

.hero h1 {
    font-size: 3em;
}

.hero p {
    font-size: 1.2em;
}

.btn {
    margin-top: 15px;
    padding: 10px 20px;
    background-color: #0078D7;
    color: white;
    border: none;
    border-radius: 5px;
    text-decoration: none;
    font-size: 1em;
}

.btn:hover {
    background-color: #0056a3;
}

/* About Section */
.about-section {
    padding: 50px;
    background-color: #fff;
    text-align: center;
}

/* Services Section */
.services-section {
    display: flex;
    justify-content: space-around;
    padding: 50px;
    background-color: #e8e8e8;
}

.service {
    width: 30%;
    text-align: center;
}

.service h3 {
    margin-bottom: 10px;
}

/* Footer */
.footer {
    text-align: center;
    padding: 10px;
    background-color: #1c1c1c;
    color: white;
}
