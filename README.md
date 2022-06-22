# Patterns [![Build status](https://ci.appveyor.com/api/projects/status/6p66n6aa38pfofp0?svg=true)](https://ci.appveyor.com/project/Lina/patterns)

## Домашнее задание к занятию «2.3. Patterns»

### Задача №1 - Заказ доставки карты (изменение даты)

Вам необходимо автоматизировать тестирование новой функции формы заказа доставки карты:

![image](https://user-images.githubusercontent.com/91609556/174998952-f31c19ed-e0d6-4f20-8f3d-771be094f54e.png)

Тестируемая функциональность: если заполнить форму повторно теми же данными за исключением "Даты встречи", то система предложит перепланировать время встречи:

![image](https://user-images.githubusercontent.com/91609556/174999182-48b76916-ad53-4e8e-9913-00d11f4c3a64.png)

После нажатия на кнопке "Перепланировать" произойдёт перепланирование встречи:

![image](https://user-images.githubusercontent.com/91609556/174999323-6023bd52-282a-418b-8084-9e2a93e901c3.png)

Обратите внимание, что Faker может генерировать не совсем в нужном для вас формате.
