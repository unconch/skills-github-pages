/* Reset some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #121212;
    color: #fff;
    line-height: 1.6;
}

h1, h2 {
    font-weight: bold;
    color: #fff;
}

.intro {
    height: 100vh;
    background: linear-gradient(135deg, #ff6f61, #ff9a8b);
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
}

.intro h1 {
    font-size: 4rem;
    margin-bottom: 20px;
}

.intro p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

.btn {
    background-color: #fff;
    color: #ff6f61;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 30px;
    transition: all 0.3s ease;
}

.btn:hover {
    background-color: #ff9a8b;
    color: #fff;
}

.about {
    background-color: #222;
    padding: 60px 20px;
    text-align: center;
}

.about h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.about p {
    font-size: 1.1rem;
    max-width: 800px;
    margin: 0 auto;
    line-height: 1.8;
}

footer {
    background-color: #121212;
    color: #aaa;
    text-align: center;
    padding: 20px 0;
    font-size: 0.9rem;
}
