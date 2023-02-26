# ruobr-api-java
Модуль на JAVA, позволяющий получать и использовать информацию с [Электронного Дневника](https://cabinet.ruobr.ru/login/).
## Использование:
Требования: JDK-8 и выше
```java
RuobrAPI api = new RuobrAPI("username", "password");
JSONObject json = api.getUser();
Map<String, Object> hashMap = api.toMap(json);
{'status': 'child', 'last_name': 'Зубенко', 'school_terrirtory_id': 1, 'user_img': 'https://ruobr.ru/mediac/avatars/48ba6326740e49d6a3c9ac01fedff9d7.JPEG', 'school_is_tourniquet': 0, 'user_id': 115654529, 'school_is_food': 5, 'school': 'МБОУ "СОШ №69"', 'group': '11А', 'success': True, 'push_settings': {'school_news': 0, 'attendance': 0, 'homework': 0, 'mau_balance': 0, 'tourniquet': 1, 'mark': 1}, 'middle_name': 'Петрович', 'id': 4694228, 'readonly': 0, 'first_name': 'Михаил', 'birth_date': '2004-10-10', 'gps_tracker': False}
```
## Функции
Подробная информация о всех функиях: [тут](./examples/index.md).

## Важно!
Автор проекта не имеет отношения к ООО "МИРИТ". Автор не несёт ответственность за последствия его использования от сторонних лиц. Исходный код находится в общем доступе
Идея модуля была взята с [другого рпеозитория на Python](https://github.com/raitonoberu/ruobr_api)

