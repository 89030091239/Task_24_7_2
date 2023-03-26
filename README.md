# ЗАДАНИЕ 24.7.2 (HW-04)
У нас есть готовая библиотека с реализацией основных методов, но остались ещё два нереализованных метода.
**Это и будет первым практическим заданием:** посмотреть документацию к имеющимся *API*
-методам [на сайте] : https://petfriends.skillfactory.ru/apidocs/#/.
***
Как вы уже изучали ранее, видов тестирования много, соответственно, и тест-кейсов может быть очень много.
Мы с вами написали пять простых позитивных тестов, проверяющих функционал с корректными данными, ожидая, что всё
пройдёт хорошо. Наша задача — убедиться, что система возвращает статус с кодом 200.
***
Но как будет реагировать тестируемое приложение, если мы в параметрах передадим слишком большое значение или вообще его
не передадим? Что будет, если мы укажем неверный ключ авторизации и так далее?
Найти методы, которые ещё не реализованы в библиотеке, и написать их реализацию в файле **api.py**.
Подумайте над вариантами тест-кейсов и напишите ещё 10 различных тестов для данного *REST API*-интерфейса.
Готовые тест-кейсы разместите на *GitHub* и пришлите ссылку в форму ниже.
***

## Тесты
1. test_get_api_key_for_valid_user
2. test_get_all_pets_with_valid_key
3. test_add_new_pet_with_valid_data
4. test_successful_update_self_pet_info
5. test_not_successful_update_another_user_pet_info
6. test_add_new_simple_pet_with_valid_data
7. test_must_not_add_pet_photo_with_incorrect_extension
8. test_add_pet_foto
9. test_not_get_api_key_with_invalid_user_password
10. test_not_get_my_pets_with_not_valid_email
11. test_not_get_my_pets_with_not_valid_key
12. test_add_must_not_new_pet_with_not_valid_name
13. test_must_not_add_new_pet_with_empty_strings
14. test_must_not_add_new_pet_with_not_valid_animal_type
15. test_must_not_add_new_pet_with_not_valid_age
16. test_must_not_add_new_pet_with_not_valid_key
17. test_successful_add_pet_photo_by_alien_id
18. test_add_new_simple_pet_with_not_valid_data
19. test_no_successful_delete_self_pet_with_not_valid_id
20. test_successful_delete_self_pet
21. test_сleaning_up_after_testing

