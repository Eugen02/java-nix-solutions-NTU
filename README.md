# java-nix-solutions-NTU
Изложение предметной области для работы по лабораторным с java

Предметная область:

ремонтное агентство

Существуют роли: менеджер, мастер, пользователь.
Зарегистрированный пользователь может создавать заявку на ремонт. Также у пользователя есть счет, с которого осуществляется оплата за ремонт.
Менеджер имеет возможность управлять заявками пользователя:
- назначить мастера;
- определить стоимость работ;
- изменить статус заявки "ждет оплату", "оплачено", "отменен".
Менеджер также возможность пополнить счет пользователя.
Мастер имеет возможность выбрать из списка заявку на ремонт и изменить ее статус на "в работе" или "выполнено". После того, как заявка была выполнена, пользователь имеет возможность оставить отзыв о работе мастера.
Менеджер должен иметь возможность посмотреть отчет со списком заявок, где он может провети по:
- по дате заявки;
- статуса заявки;
- по стоимости.

Также менеджер должен иметь возможность фильтровать заказ:
- по статусу;
- за мастером, выполняющим / выполнял заказ. 



UML link: https://lucid.app/lucidchart/37eea9ad-0280-4ade-8540-19520b6f82b8/edit?page=0_0#
