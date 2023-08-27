# Marvel_react

Marvel informatio portal, который основан на Marvel API, содержит данные о персонажах и комиксах, которые есть внутри этой вслеленной.

Проект представлен с помощью функциональных компонентов и хуков useState, useEffect, useCallback, useMemo. В проекте реализованы следующие задачи с помощью React:

- по нажатию кнопки с помощью запроса на сервер API осуществляется трансформация данных в компонент рандомного персонажа, который содержит информацию о нем, фото и рабочие ссылки, которые ведут на страницы этого персонажа;
- отображение списка персонажей c помощью анимации React Transition Group, которых можно выбирать, и подгружать список комиксов с их участием;
- формирование компонента присходит в зависимости от его состояния с использованием принципа Finite-state machine;
- показ компонента спинера при загрузке и компонента, сообщающего об ошибке;
- поиск по имени персонажа в форме при помощи библиотеки Formik и библиотеки валидации Yup;
- использование собственного хука;
- использование предохранителей Error Boundaries, чтобы правильно перехватывать ошибки в приложении;
- навигация в приложении с помощью React Router v5+ с использованием динамических путей;
- оптимизация скорости работы приложения с помощью React.memo;
- по клику на кнопку с помощью запроса на сервер API происходит дозагрузка персонажей;
- проверка типов данных с помощью PropTypes;
- вставка элементов через props.children;
- выделение карточки персонажа с помощью хука useRef и переключение карточек с клавиатуры;
- SEO-оптимизация приложения при помощи библиотеки React-helmet.
