/* Общие стили */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
}

/* Главная страница */
.header {
    background: #333;
    color: #fff;
    padding: 50px 0;
    text-align: center;
}

.header h1 {
    font-size: 2.5em;
}

.header p {
    font-size: 1.2em;
    margin-top: 10px;
}

/* О разделе "Обо мне" */
.about {
    padding: 50px 0;
    background: #fff;
}

.about h2 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
}

.about p {
    text-align: center;
    font-size: 1.2em;
}

/* Портфолио */
.portfolio {
    background: #f9f9f9;
    padding: 50px 0;
}

.portfolio h2 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
}

.gallery {
    display: flex;
    gap: 20px;
    justify-content: center;
}

.gallery-item img {
    width: 100%;
    max-width: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Услуги */
.services {
    padding: 50px 0;
    background: #fff;
}

.services h2 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
}

.services ul {
    list-style: none;
    text-align: center;
}

.services li {
    font-size: 1.2em;
    margin: 10px 0;
}

/* Контакты */
.contact {
    padding: 50px 0;
    background: #f9f9f9;
}

.contact h2 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
}

.contact p {
    text-align: center;
    font-size: 1.2em;
}

.contact form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    max-width: 500px;
    margin: 0 auto;
}

.contact input, .contact textarea {
    width: 100%;
    padding: 10px;
    font-size: 1em;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact button {
    padding: 10px 20px;
    font-size: 1.2em;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact button:hover {
    background-color: #444;
}

/* Футер */
footer {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}
