# e-robota-api


Дипломний проєкт:  CRM-система єРобота (Angular, Spring)

Ласкаво просимо до єРобота - інноваційної комерційної CRM-системи, створеної з метою забезпечити повний контроль та ефективне управління ресурсами вашої компанії. Наша CRM-система об'єднує у собі ряд потужних функцій для зручної роботи з даними працівників, обліку матеріальних цінностей та оперативного інформування, що робить роботу вашої команди більш організованою та продуктивною.
Головні функції єРобота:
-	Зручний облік даних працівників для HR. Завдяки інтуїтивно зрозумілому інтерфейсу, кадровик може легко створювати та зберігати персональні дані про працівників, вносити зміни у контактні дані, дати народження, підтримувати актуальну інформацію про посаду та інші зміни.
-	Облік матеріальних цінностей для бухгалтера. Наша CRM-система дозволяє бухгалтеру зручно відстежувати всі матеріальні цінності компанії. Кожному об'єкту призначається унікальний QR-код, який містить додаткову інформацію про цю річ. Бухгалтер може легко сканувати QR-коди і швидко знаходити річ в таблиці, що уникне необхідності писати маркувати об'єкти.
-	Оперативне інформування без щоденних нарад. Прес-служба або секретар публікують оперативну інформацію про останні події, підписані накази та розпорядження через персональний кабінет в системі, працівнику залишається лише переглянути стрічку новин. Це дозволяє збільшити продуктивність роботи.
-	Система ролей. Кожен співробітник має свій персональний кабінет з обмеженим доступом до даних, відповідно до його ролі в компанії. HR-фахівець може вносити та редагувати дані про працівників, бухгалтер контролює матеріальні цінності, а фахівець прес-служби інформує про останні події.
-	Адміністраторський доступ.  Адміністратор має повний контроль над системою і може змінювати ролі співробітників, керувати правами доступу та налаштуваннями системи.

З єРобота, ваша компанія зможе досягати нових висот ефективності та продуктивності. Наша CRM-система проста у використанні, але потужна у можливостях, щоб задовольнити потреби вашого бізнесу.


## Run SQL insert statements first
```
create database erobota_db;
use erobota_db;

INSERT INTO roles(name) VALUES('ROLE_EMPLOYEE');
INSERT INTO roles(name) VALUES('ROLE_HR');
INSERT INTO roles(name) VALUES('ROLE_ACCOUNTANT');
INSERT INTO roles(name) VALUES('ROLE_NEWS_MAKER');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');
