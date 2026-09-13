# Привет! 👋
<p>Я Никита Пирогов – веб-разработчик и аналитик данных. Сочетаю аналитику с разработкой, чтобы строить полный пайплайн решения: от сбора данных и обучения ML-моделей до создания интерактивных веб-приложений для пользователей.</p>
<p>В настоящее время обучаюсь на 3-м курсе Санкт-Петербургского государственного университета (СПбГУ) по направлению <b>Фундаментальная информатика и информационные технологии</b>, профиль Большие данные. В университете изучаю Прикладную Математику, основы Computer Science и Машинное Обучение, а параллельно основной учебе самостоятельно прохожу курсы по TypeScript.</p>

<!-- [![Portfolio](https://img.shields.io/badge/Портфолио-000000?style=for-the-badge&logo=safari&logoColor=white)]( !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! ) -->
<!-- add LinkedIn ???? -->
<!-- add telegram ???? -->

## Мой технологический стек
### Веб-разработка
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) 
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black&style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### Аналитика данных
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![SQL](https://img.shields.io/badge/SQL-006488?style=for-the-badge&logo=postgresql&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

### Вспомогательные технологии
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## Языковые навыки
![English](https://img.shields.io/badge/Английский%20язык-C1%20(Advanced)-006488?style=for-the-badge&logoColor=white)

## Портфолио (веб)
### Конструктор
[![Live](https://img.shields.io/badge/Посетить%20вебсайт-1f6feb)](https://const-n-s-pirogov-j35i.onreza.app)
[![Repo](https://img.shields.io/badge/GitHub-Конструктор-FFC017?style=flat&logo=github&logoColor=white)](https://github.com/ProofMrNick/ejs_project9)

Конструктор – это фуллстек веб-приложение для ведения блога, предоставляющее инструменты как для написания статей через графический интерфейс, так и для чтения статей других пользователей и взаимодействия с ними.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)

- **Frontend**: HTML, CSS, JavaScript (с шаблонизатором EJS)
- **Backend**: Node.js, Express.js

Основные возможности:
- личный кабинет (аккаунт) с дашбордом статей 
- создание, редактирование, удаление, скрытие статей от других
- закрепление особо важных статей на самом верху ленты
- чтение статей других пользователей и реакции в виде кнопок “Понравилось” и “Не понравилось” с защитой от накрутки
- уникальные ссылки на статьи, которыми можно делиться
- адаптируемость под экраны как компьютеров, так и мобильных устройств

Технические характеристики приложения:
- server-side rendering (SSR)
- хранение данных в JSON-файле посредством автоматических коммитов в репозиторий Github с зашифрованной БД (позволяет избежать потери данных на эфемерном хостинге)
- выборка данных на эндпойнте с фильтрацией скрытого контента, пагинацией и хронологической сортировкой

## Портфолио (аналитика)
### Cooking Time Predictor
[![Repo](https://img.shields.io/badge/GitHub-CookingTimePredictor-006488?style=flat&logo=github&logoColor=white)](https://github.com/ProofMrNick/CookingTimePredictor)

Cooking Time Predictor – ML-пайплайн полного цикла: от сбора данных с [кулинарного сайта](https://foodnetwork.co.uk) до обучения и тестирования модели и сохранения артефакта. Предсказывает время приготовления блюда в минутах по названию, описанию, ингредиентам и шагам приготовления.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

Обзор <br>
Random Forest (RF) по логарифмированному таргету: MAE 10.38 мин (Median AE 6.92 мин). Для блюд с временем приготовления до 1 часа более 90% предсказаний имеют ошибку в пределах 20 минут. Данные: ~2500 рецептов, спаршенных с кулинарного сайта [foodnetwork.co.uk](https://foodnetwork.co.uk). 

Схема пайплайна <br>
парсинг -> предобработка и очистка данных -> EDA и разделение (80/20) -> feature engineering + кодирование -> hyperparameter tuning (с 3-fold cross-val) -> обучение модели -> тестирование и вывод метрик -> сохранение обученной модели

Результаты <br>
Сравнивались модели: RF, Voting Regressor (RF + KNN + линейная), Gradient Boosing (GB). Результат – RF показал наименьшую ошибку.
Итоговые метрики RF: 
- MAE: 10.38 мин 
- RMSE: 15.82
- Median AE: 6.92 мин
- R^2: 0.68

## Научные публикации
### Сильная и слабая масштабируемость современных вычислительных систем
#### Strong and weak scaling of modern computing systems

[![РИНЦ](https://img.shields.io/badge/Смотреть%20на-РИНЦ-f26c4f?style=flat)](https://elibrary.ru/jmjnqc) <br>
Давыдов Е. Б., ***Пирогов Н. С.***, Ибатуллин Е. В. // *Сборник научных трудов Всероссийской научно-практической конференции "ТЕОРИЯ И ПРАКТИКА СОВЕРШЕНСТВОВАНИЯ ОТЕЧЕСТВЕННЫХ СИСТЕМ СВЯЗИ, АВТОМАТИЗАЦИИ И ИНФОРМАЦИОННОЙ БЕЗОПАСНОСТИ"* – СПб, 2025 – Т. 1, С. 219-228 – УДК 004.031.

- **Индексация:** РИНЦ
- **EDN:** JMJNQC
- **eLIBRARY ID:** 91656421

<p>В статье рассматриваются ключевые аспекты современных систем высокопроизводительных вычислений. Анализируются проблемы сильной масштабируемости. Представляется концепция слабой масштабируемости, позволяющая эффективно работать с увеличивающимся объемом параллельных вычислений. Обсуждается важность балансировки мощности оборудования и параллелизации задач для обеспечения отзывчивости вычислительной инфраструктуры. Статья подчеркивает переход от простой вертикальной масштабируемости к гибким решениям горизонтального масштабирования для обеспечения надежности и эффективного использования ресурсов для соответствия растущим требованиям современных вычислительных приложений.</p>
<p><b>Ключевые слова:</b> HPC, strong scaling, weak scaling, закон Амдала, закон Густафсона, распределенные системы.</p>

## Давайте знакомиться!
<!-- [![Portfolio](https://img.shields.io/badge/Портфолио-000000?style=for-the-badge&logo=safari&logoColor=white)]( !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! ) -->
[![Почта](https://img.shields.io/badge/Почта-0076fe?style=for-the-badge&logo=maildotru)](mailto:n.s.pirogov@mail.ru)
<!-- add LinkedIn ???? -->
<!-- add telegram ???? -->
