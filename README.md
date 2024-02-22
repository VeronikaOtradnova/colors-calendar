Я тестировала результат своей работы вручную и с помощью тестов (jest и react-testing-library).

Чтобы проверить работу поля с датой, я нажимала на стрелки вправо и влево и следила за тем, чтобы дата  менялась. Проверяла, что стрелка вправо неактивна, если дата в поле совпадает с сегодняшней датой. 
Кликала по дате и смотрела, что календарь открылся. 
Написала тесты, которые проверяют то же самое, плюс проверяют, чтобы дата в поле совпадала с currentDate стейте.

Чтобы проверить работу блока с данными за день вручную, я открывала день, который до этого не редактировала, выбирала цвет и наблюдала за тем, как список для выбора цвета сменяется надписью с выбранным цветом и кнопкой открытия редактора. 
Потом проверяла работу кнопки "изменить цвет": нажимала на неё, чтобы редактор открылся, потом нажимала снова, чтобы он закрылся.
Написала тесты, которые делают то же самое.

Чтобы проверить работу календаря, выбирала дату не позднее сегодняшней и ожидала, что дата в верхнем блоке изменится на выбранную, а контент будет соответствовать цветовой метке у этого календаря. Кликала по дате из будущего и ожидала, что она не выделится. 
Блок с месяцем и стрелками проверяла по тому же принципу, что и самый первый блок с датой и стрелками.
Написала тесты, которые делают то же самое.

Также держала консоль открытой, чтобы видеть и сразу исправлять возможные ошибки и предупреждения. И меняла ширину экрана, чтобы проверять, как отображается вёрстка на разных экранах.