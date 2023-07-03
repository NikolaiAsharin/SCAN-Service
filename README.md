# SCAN-Service

<h1>Постановка задачи</h1> 
<p>Компания СКАН разработала новый API для поиска публикаций о компании (юридическом лице) в средствах массовой информации по его ИНН. Серверная часть приложения уже готова, ваша задача — разработать клиентскую часть.</p>
<h1>Функциональные требования</h1> 
<p>Клиентская часть сервиса состоит из:</p>
<ul>
<li>главной страницы.</li>
<li>формы авторизации.</li>
<li>формы для ввода параметров запроса.</li>
<li>страницы с выводом результатов запроса.</li>
</ul>
<p>Макет, подготовленный дизайнерами, находится по <a href=https://www.figma.com/file/u3MOjzYnTnirz712GrLbFv/%D0%9C%D0%B0%D0%BA%D0%B5%D1%82-%D0%A1%D0%9A%D0%90%D0%9D?type=design&node-id=0-1&mode=design&t=3R6dMajt7SwQ2Xgb-0>ссылке.</a></p>

<h1>Требования к вёрстке</h1> 
<p>Вёрстка должна соответствовать макету. Добиваться Pixel Perfect соответствия не обязательно, но основные моменты должны быть соблюдены:</p>
<ul>
<li>наличие всех элементов интерфейса</li>
<li>цветовая гамма</li>
<li>шрифты</li>
<li>размеры</li>
<li>отступы</li>
</ul>
<p>Приложение должно корректно отображаться и работать на мобильных устройствах. Дизайн для мобильной версии вы найдёте в макете.
Соблюдайте семантическую вёрстку. На каждой странице должны присутствовать разделы &lt;header&gt;, &lt;main&gt; и &lt;footer&gt;, а также заголовок &lt;h1&gt;. Кнопки должны быть реализованы элементом &lt;button&gt;, выпадающий список — элементом &lt;select&gt; и так далее.<br><br>
Если какой-либо элемент доступен для взаимодействия (ссылка, кнопка), при наведении курсора должен появляться cursor: pointer.<br>
Внешний вид самого элемента тоже должен меняться при наведении курсора. Пример: нижнее подчёркивание текста у ссылки, другой цвет фона у кнопки.<br>
Используйте любой вариант подключения стилей на ваше усмотрение:</p>
<ul>
<li>общий файл стилей проекта</li>
<li>CSS-модули</li>
<li>специальные React-библиотеки для стилизации компонентов (например, Styled Components)</li>
</ul><br>
<p>Использовать селекторы по тегу и ID для задания стилей не рекомендуется, старайтесь отдавать предпочтение классам.<br>
Лучше всего экспортировать картинки из Figma в формате SVG, чтобы качество изображений было стабильным на разных разрешениях.</p><br><br>

<h1>Требования к коду</h1>
<ul>
<li>Проект должен был выполнен на React</li>
<li>Интерфейс должен быть поделён на компоненты. Перед началом работы обдумайте, какие компоненты вы будете использовать. Деление должно быть логичным и оправданным</li>
<li>Проект будет работать со множеством данных. Рекомендуем использовать более продвинутый инструмент хранения и изменения данных, чем обычный state. Например, useReducer, React Context или Redux</li>
</ul><br><br>
<h2>При написании кода старайтесь следовать принципам:</h2>
<ul>
<li>KISS (Keep It Short and Simple — не усложняй)</li>
<li>DRY (Don’t Repeat Yourself — не повторяйся)</li>
<li>Вы не ограничены в использовании любых инструментов и дополнительных библиотек (например, для реализации карусели). Но старайтесь следить за тем, чтобы их применение было оправдано и не усложняло код без необходимости</li></ul>

<h2>Прочие требования</h2>
<ul>
<li>Пишите код аккуратно, с соблюдением форматирования и отступов</li>
<li>Осмысленно называйте компоненты, переменные и функции</li>
<li>Используйте современный синтаксис: функциональные React-компоненты и хуки, стрелочные функции, декомпозицию и так далее</li>
<li>При размещении проекта на GitHub не забудьте добавить папку node_modules в файл .gitignore, чтобы она не попала в ваш репозиторий. О том, как настроить .gitignore и почему папки node_modules не должно быть в репозитории, читайте в этой <a href=https://cpab.ru/chto-takoe-fajl-gitignore-i-kak-ego-nastroit-cloudsavvy-it/>статье.<a></li>
</ul>
