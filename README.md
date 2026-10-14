[style.css](https://github.com/user-attachments/files/33420387/style.css)
# seenu* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f6f8;
    color: #333;
}

header {
    background-color: #17365d;
    color: white;
    text-align: center;
    padding: 30px 15px;
}

header h1 {
    font-size: 28px;
    margin-bottom: 10px;
}

nav {
    background-color: #0d2238;
    text-align: center;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 12px;
    font-weight: bold;
}

nav a:hover {
    color: #ffd700;
}

section {
    max-width: 1100px;
    margin: auto;
    padding: 50px 20px;
}

section h2 {
    text-align: center;
    color: #17365d;
    margin-bottom: 25px;
    font-size: 28px;
}

.hero {
    max-width: none;
    text-align: center;
    background-color: #dceaf7;
    padding: 80px 20px;
}

.hero h2 {
    font-size: 36px;
}

.hero p {
    max-width: 750px;
    margin: 20px auto;
    font-size: 18px;
}

.button {
    display: inline-block;
    background-color: #17365d;
    color: white;
    text-decoration: none;
    padding: 12px 25px;
    border-radius: 5px;
}

.course-container {
    display: flex;
    gap: 20px;
    justify-content: center;
    flex-wrap: wrap;
}

.course {
    background-color: white;
    padding: 25px;
    width: 300px;
    border-radius: 8px;
    box-shadow: 0 3px 10px #ccc;
}

.course h3 {
    color: #17365d;
    margin-bottom: 15px;
}

#facilities {
    background-color: white;
}

#facilities ul {
    max-width: 600px;
    margin: auto;
}

#facilities li {
    padding: 8px;
}

article {
    background-color: white;
    padding: 25px;
    margin: 20px auto;
    max-width: 800px;
    border-left: 5px solid #17365d;
    box-shadow: 0 2px 8px #ddd;
}

article h3 {
    color: #17365d;
    margin-bottom: 10px;
}

article a {
    display: inline-block;
    margin-top: 10px;
    color: #0645ad;
}

#contact {
    background-color: #e9f0f7;
    text-align: center;
}

footer {
    background-color: #17365d;
    color: white;
    text-align: center;
    padding: 20px;
}

@media (max-width: 700px) {
    header h1 {
        font-size: 21px;
    }

    nav a {
        display: block;
        margin: 8px;
    }

    .hero h2 {
        font-size: 28px;
    }

    .course {
        width: 100%;
    }
}
