/* Reset de márgenes y padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header .logo h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin-top: 0.5rem;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('../img/hero.jpg') no-repeat center center/cover;
    color: #fff;
    height: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 1rem;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
}

.hero .btn {
    background: #333;
    color: #fff;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 5px;
}

.destacados {
    padding: 2rem;
    text-align: center;
}

.destacados h2 {
    margin-bottom: 2rem;
}

.destacados .productos {
    display: flex;
    justify-content: center;
    gap: 2rem;
}

.destacados .producto {
    border: 1px solid #ddd;
    padding: 1rem;
    border-radius: 5px;
    text-align: center;
}

.destacados .producto img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 1rem;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}
