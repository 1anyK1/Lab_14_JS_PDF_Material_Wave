
# Вступительный экзамен для Front-end разработчика

## Задача

Вашей задачей является создание веб-страницы с резюме, которое должно быть сверстано по данному шаблону. Страница должна иметь возможность изменять текст элементов и предоставлять кнопку "Скачать" для скачивания резюме в формате PDF. В качестве дополнительного задания, необходимо анимировать клики на элементы резюме с помощью CSS-анимаций и добавить эффект "Material Wave".

### Основные требования:

1. Создайте макет веб-страницы с резюме на основе предоставленного шаблона. (Сделайте fork этого репозитория)
2. Добавьте возможность редактирования текстовых элементов резюме, сохраняя изменения внутри элементов.
3. Реализуйте кнопку "Скачать", которая преобразует текущую версию резюме в формат PDF и начинает загрузку файла на компьютер пользователя.
   - Допустимо использовать бибилиотеки для преобразования html в pdf (Например React PDF), но можно и просто подложить pdf и скачивать его по ссылке
4. Все изменения элементов резюме должны быть анимированы с помощью CSS-анимаций.
5. Разработка должна быть с использованием базовых технологий (html, js, css) без использования сторонних библиотек и фреймворков.

### Дополнительные задачи:

1. Адаптивность: страница должна корректно отображаться на различных устройствах и разрешениях экрана.
2. Material Wave (ripple): Добавьте "Material Wave" эффект при взаимодействии с элементами страницы (кликах на элементах).
3. Оптимизация: обеспечьте быструю загрузку страницы и сохранение введенных данных в случае обновления страницы.


### Сдача экзамена:

Ожидается, что вы выложите ваш проект на публичный репозиторий (например, GitHub), напишите краткое описание и инструкцию по установке (если применимо). Предоставьте ссылку на репозиторий и рабочий пример приложения (например, используя GitHub Pages) для проверки.

[Как публиковать статические сайты на GitHub Pages?](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

Удачи на экзамене!

[Ссылка на шаблон резюме](https://www.figma.com/design/0lCK90FekbMPNJOOUuiIV8/exam-cv?node-id=0-3&t=51CUbfwKNoVYLV1V-1)

Для проверки семантики верстки и качества JS кода существуют различные инструменты и сервисы.

**Для проверки семантики верстки будет использовано:**

Валидатор HTML от W3C: https://validator.w3.org

**Для проверки качества JS кода будут использоваться инструменты:**

1. JSHint: https://jshint.com
   JSHint - это инструмент для анализа кода, который проверяет наличие некорректного, небезопасного или несоответствующего стандартам кода в вашем JavaScript.

2. ESLint: https://eslint.org
   ESLint - мощный линтер для JavaScript, который выявляет ошибки и несоответствующий коду стиля. Установите его в качестве пакета Node.js или интегрируйте с вашим редактором кода.

**Что может вам помочь?**

Prettier: https://prettier.io
   Prettier - это инструмент форматирования кода, который автоматически обрабатывает ваш JavaScript (а также CSS, HTML и другие языки), чтобы сделать его более читабельным и соответствующим стандартам.

