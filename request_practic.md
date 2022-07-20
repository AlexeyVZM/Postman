# Postman
В данном каталоге приведены практические примеры выпонения основных автотестов при работе с API при помощи Postman.
1) [http://162.55.220.72:5005/first](http://162.55.220.72:5005/first)
1. Отправить запрос.
2. Статус код 200
3. Проверить, что в body приходит правильный string.

![check_response_body](https://github.com/AlexeyVZM/Postman/blob/main/request_practic/check_response_body.jpg)


[http://162.55.220.72:5005/user_info_3](http://162.55.220.72:5005/user_info_3)
Отправить запрос.

![body_POST_user_info_3](https://user-images.githubusercontent.com/102965578/179921888-a13ee117-af5c-4d14-936b-0340f96430b2.jpg)

2. Статус код 200
3. Спарсить response body в json.
4. Проверить, что name в ответе равно name s request (name вбить руками.)
5. Проверить, что age в ответе равно age s request (age вбить руками.)
6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)
7. Спарсить request.
8. Проверить, что name в ответе равно name s request (name забрать из request.)
9. Проверить, что age в ответе равно age s request (age забрать из request.)
10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
11. Вывести в консоль параметр family из response.
12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)
![POST_user_info_3](https://user-images.githubusercontent.com/102965578/179917063-bbd18cc9-9b95-4480-bc01-e643fd9ace3c.jpg)

![POST_user_info_3_(2)](https://user-images.githubusercontent.com/102965578/179917096-011d00ff-bd90-4768-98e0-888fc34c71f5.jpg)
