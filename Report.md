## Краткое описание

<5.10.20> - <6.10.20> было проведено <Функциональное , пользовательское, тестирование установки, интеграционное> приложения <KeyValidator,OpenJDK11 >.

На тестирование затрачено: <12ч>

В результате тестирования выявлены следующие дефекты:
* <Ошибка в валидных и невалидных ключах>

## Описание процесса тестирования
**1.   Установка OpenJDK11 согласно инструкции**  

- [инструкция по установке OpenJDK 11]( https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md) 

- **ожидаем результат в терминале :** 

$ java -version
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)

- **фактический результат в терминале**

$ java -version
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
![фатический результат установки OpenJDK11](https://user-images.githubusercontent.com/69162015/94802720-d5447580-03f0-11eb-900e-302f06bd329c.png)

**2. Приложение запускается и совместимо с Java 11**

- **Ожидаемый результат** :  Приложение запускается и совместимо с Java 11
- **Фактический результат** :  Приложение запускается и совместимо с Java 11 

**3. **Приложение работает согласно руководству использования****

- [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

**- Ожидаемый результат :** Приложение работает согласно руководству использования

**- Фактический результат :** Приложение работает согласно руководству использования.

**3.1 Проверка валидных и не валидных ключей**  

**- Ожидаемый результат** 

**_Валидные ключи:_**
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

**_Невалидные ключи:_**
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

**- Фактический результат :**
[Ошибка](https://github.com/Stepan164i/Javaqa-D.Z-1.1/issues/3) в валидных и невалидных ключах


В процессе тестирования использовались следующие артефакты*:
* < [инструкция по установке OpenJDK 11]( https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md) >
* <[Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)>
* Отчет о тестировании

В качестве тестовых данных использовались данные <https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md>:
_**Валидные ключи:**_
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

_**Невалидные ключи:**_
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:
* <64-Bit>
* < Java version "11.0.8" 2020-07-14>
* <[Git(https://github.com/Stepan164i/Javaqa-D.Z-1.1.git)>