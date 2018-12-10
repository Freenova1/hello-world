# hello-world
<!DOCTYPE html>
<html>
    <head>
        <meta lang="ru">
        <meta charset="utf-8">
        <meta content="Визитная карточка, инфа о себе">
        <link rel="stylesheet" href=Style/style.css>
        <title>Визитная карточка</title>
    </head>
    <body>
        <div class="wrapper">
            <header>
                <div class="name-page">
                    <h1>Бобров Валерий Витальевич</h1>
                </div>
                <nav class="main-nav">
                    <ul>
                        <li><a href="" alt="">Главная страница</a></li>
                        <li><a href="" alt="">Моя семья</a></li>
                        <li><a href="" alt="">Зарегестрироваться</a></li>
                    </ul>
                </nav>
            </header>
            <hr>
            <main>
                <section class="Intro">
                    <blockquote>"Самая важная страница книги-это первая!"</blockquote>
                    <h1>Не много обо мне!</h1>
                    <p>Всем привет, меня зовут <strong>Валера Бобров</strong> и это моя первая веб страница. Здесь я постараюсь отобразить все свои навыки работы с HTML и CSS.</p>
                    <p>Данная страница будет состоять из 3 частей:
                       <div class="list">
                            <ol>
                                <li>Это водная часть, где я буду применять способы форматирования текста с помощью CSS.</li>
                                <li>Вторая часть, где буду создавать таблицу по всем современным стандартам HTML 5, с использованием тегов <code>thead</code>, <code>tbody</code> и <code>tfooter</code>.</li>
                                <li>И третья часть, самая сложная, но в тоже время самая важная, это форма.</li>
                            </ol>
                        </div>
                    </p>
                </section>
                <section class="time-table">
                    <article class="1-time">
                        <h2> Всего лишь одна таблица, зато какая.</h2>
                        <table>
                            <caption>Ежедневный заработок в роли официанта</caption>
                            <thead>
                                <tr>
                                    <th>Дата:</th>
                                    <th>Количество часов:</th>
                                    <th>Рубли:</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                     <td>01.10</td>
                                     <td class="hours">8</td>
                                     <td class="money">1500</td>
                                </tr>
                                <tr>
                                     <td>02.10</td>
                                     <td class="hours">10</td>
                                     <td>2000</td>
                                </tr>
                                <tr>
                                     <td>03.10</td>
                                     <td class="hours">12</td>
                                     <td class="money">2500</td>
                                </tr>
                            </tbody>
                            <tfoot>
                                <tr>
                                     <th>Всего:</th>
                                     <td class="hours">30</td>
                                     <td class="money">6000</td>
                                </tr>
                            </tfoot>
                        </table>
                        <p>Вот столько я мог зарабатывать в ресторане, если бы я там остался, но нет! Хочу заниматься программированием!</p>
                    </article>
                </section>
                <section class="feedback">
                   <h2>Форма</h2>
                    <article class="main-info">
                        <form method="post" action="">
                                <h3>Контактная информация:</h3>
                                <label for="name">Имя</label>
                                <input type="text" id="name">
                                <br> 
                                <label for="second-name">Фамилия</label>
                                <input type="text" id="second-name">
                                <br>
                                <label for"birthday">Дата рождения</label>
                                <input type="date" id="birthday">
                                <br>
                                <label for="female">Пол</label>
                                <input type="radio" id="female" value="man" checked>Мужской
                                <input type="radio" id="female" value="woman">Женский
                                <br>
                                <label for="number">Контактный телефон</label>
                                <input type="tel" id="number">
                                <br>
                                <label for="contact-email">Контактная почта</label>
                                <input type="email" id="contact=email">
                                <br>
                                <input type="submit" value="Отправить"Б
                        </form>                        
                    </article>
                    <article class="TI-info">
                        <form method="post" action="">
                                <h3>Опрос:</h3>
                                <label for="lang">Какие языки вы знаете?</label><br>
                                <input type="checkbox" id="lang" value="HTML" checked>HTML
                                <input type="checkbox" id="lang" value="CSS">CSS
                                <input type="checkbox" id="lang" value="JavaScript">JavaScript
                                <br>
                                <label for="lang-pop">Выберите ваш любимый язык среди выше перечисленных</label><br>
                                <select id="lang-pop" name="lang-pop">
                                    <option value="HTML">HTML</option>
                                    <option value="CSS">CSS</option>
                                    <option value="JS">JavaScript</option>
                                </select>
                                <br>
                                <label for="info-self">Не много о себе</label>
                                <input type="textarea" id="info-self">
                        </form>
                    </article>
                </section>
            </main>
            <footer>
                <section class="contact-info">
                    <a href="mailto:bvalera15@gmail.com">Написать на почту</a><br>
                    Сотовый телефон: +79211926836
                </section>
                <div class="links">
                    <a href="https://vk.com/id157403986" name="Link-vk"><img src="Image/%C2%A0vk-logo.jpg" alt=""></a>
                    <a href="https://twitter.com/Freenova1" name="Link-twitter"><img src="Image/logo-twitter.png" alt=""></a>
                    <a href="https://www.instagram.com/freenova1/?hl=ru" name="Link-insta"><img src="Image/logo-insta.jpg" alt=""></a>
                </div>
            </footer>
        </div>
    </body>
</html>
