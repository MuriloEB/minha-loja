* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}

header {
    background: #333;
    color: #fff;
    padding: 20px 0;
}

header .logo {
    float: left;
    margin-left: 20px;
}

header nav {
    float: right;
    margin-right: 20px;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    margin-left: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('banner.jpg') no-repeat center center/cover;
    color: #fff;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero h2 {
    font-size: 3em;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 20px;
}

.hero .button {
    background: #ff4747;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    font-size: 1em;
    border-radius: 5px;
}

.ofertas, .produtos {
    padding: 40px 0;
}

h2 {
    text-align: center;
    margin-bottom: 40px;
}

.grid {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.item {
    flex: 1 1 200px;
    margin: 10px;
    padding: 20px;
    border: 1px solid #ddd;
    text-align: center;
}

.item img {
    max-width: 100%;
    height: auto;
}

.item h3 {
    margin: 20px 0 10px;
}

.item p {
    font-size: 1.2em;
    color: #333;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

@media (max-width: 768px) {
    .hero h2 {
        font-size: 2em;
    }
    .hero p {
        font-size: 1em;
    }
    .header nav {
        text-align: center;
    }
    .header nav ul {
        padding: 0;
    }
    .header nav ul li {
        display: block;
        margin: 0;
        padding: 10px 0;
    }
    .item {
        flex: 1 1 100%;
    }
}
