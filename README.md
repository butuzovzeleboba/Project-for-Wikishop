# Overview
The online store "Wikishop" is launching a new service that allows users to edit and supplement product descriptions, similar to wiki communities. Customers can suggest their edits and comment on changes made by others. To ensure content quality, the store needs a tool that will automatically detect toxic comments and send them for moderation.

Objectives
1. Identify toxic comments: Develop a machine learning model to automatically detect toxic comments.
2. Ensure high accuracy: The F1 score on the test set should be at least 0.75.

Methodology
- Data loading: Obtain comment data and their toxicity from the toxic_comments.csv file.
- Data analysis: Conduct exploratory data analysis (EDA) using statistical methods and visualization tools. Identify characteristics of toxic comments, such as the frequency of profanity, presence of insults, threats, etc.
- Text processing: Apply natural language processing (NLP) techniques to prepare the text for model training. This includes:
  - Lemmatization
  - Removal of stop words
  - Text vectorization (e.g., using TF-IDF or word2vec)
- Model training: Train several machine learning models with different hyperparameters for classifying comments as toxic or non-toxic. Split the data into training and test sets, with the test set comprising 20% of the original data.
- Model evaluation: Evaluate model performance on the test set using metrics such as F1, precision, and recall. Draw conclusions about which model best suits the task.

Expected Results
1. Improved content quality: The model will help automatically detect and send toxic comments for moderation, improving site content quality and enhancing customer interaction experience.
2. Moderator time savings: Automating the detection of toxic comments will allow moderators to focus on more important tasks, saving their time and effort.
3. Increased customer satisfaction: Creating a safe and comfortable environment for communication on the site will increase customer satisfaction and strengthen their loyalty to the store.

Conclusion
Developing a machine learning model for detecting toxic comments will help the online store "Wikishop" improve content quality, save moderator time, and enhance customer interaction experience. Using comment and toxicity data will enable the creation of an effective tool for automatic moderation, increasing the store's competitiveness in the e-commerce market.

# Обзор
Интернет-магазин «Викишоп» запускает новый сервис, позволяющий пользователям редактировать и дополнять описания товаров, как в вики-сообществах. Клиенты могут предлагать свои правки и комментировать изменения других. Для обеспечения качества контента магазину нужен инструмент, который будет автоматически выявлять токсичные комментарии и отправлять их на модерацию.

Цели
1. Выявление токсичных комментариев: Разработать модель машинного обучения для автоматического определения токсичных комментариев.
2. Обеспечение высокой точности: Значение метрики F1 на тестовой выборке должно быть не ниже 0.75.

Методология
- Загрузка данных: Получаю данные о комментариях и их токсичности из файла toxic_comments.csv.
- Анализ данных: Провожу исследовательский анализ данных (EDA) с использованием статистических методов и инструментов визуализации. Идентифицирую особенности текста токсичных комментариев, такие как частота употребления ненормативной лексики, наличие оскорблений, угроз и т.д.
- Обработка текста: Применяю методы обработки естественного языка (NLP) для подготовки текста к обучению модели. Включаю в обработку следующие этапы:
  - Лемматизация
  - Удаление стоп-слов
  - Векторизация текста (например, с использованием TF-IDF или word2vec)
- Обучение моделей: Обучаю несколько моделей машинного обучения с различными гиперпараметрами для классификации комментариев на токсичные и нетоксичные. Разделяю данные на обучающую и тестовую выборки, где тестовая выборка составляет 20% от исходных данных.
- Оценка моделей: Оцениваю производительность моделей на тестовой выборке, используя метрики F1, precision и recall. Делаю выводы о том, какая модель лучше всего подходит для данной задачи.

Ожидаемые результаты
1. Повышение качества контента: Модель поможет автоматически выявлять и отправлять на модерацию токсичные комментарии, что повысит качество контента на сайте и улучшит впечатление от взаимодействия с магазином.
2. Экономия времени модераторов: Автоматизация процесса выявления токсичных комментариев позволит модераторам сосредоточиться на более важных задачах, экономя их время и усилия.
3. Повышение удовлетворенности клиентов: Создание безопасной и комфортной среды для общения на сайте повысит удовлетворенность клиентов и укрепит их лояльность к магазину.

Заключение
Разработка модели машинного обучения для выявления токсичных комментариев поможет интернет-магазину «Викишоп» повысить качество контента, экономить время модераторов и улучшить впечатление от взаимодействия с магазином. Использование данных о комментариях и их токсичности позволит создать эффективный инструмент для автоматической модерации, что повысит конкурентоспособность магазина на рынке электронной коммерции.
