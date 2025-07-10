/* style.css 简洁大方风格 */

body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    background: #f9f9f9;
    color: #333;
    text-align: center;
}

header {
    background: #fff;
    padding: 20px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.logo {
    height: 60px;
    margin-bottom: 10px;
}

h1 {
    font-size: 24px;
    margin: 0;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 40px;
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
}

.gallery img {
    max-width: 300px;
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    cursor: pointer;
    transition: transform 0.3s;
}

.gallery img:hover {
    transform: scale(1.05);
}

footer {
    background: #fff;
    padding: 10px;
    font-size: 14px;
    color: #888;
    box-shadow: 0 -2px 4px rgba(0,0,0,0.05);
}
