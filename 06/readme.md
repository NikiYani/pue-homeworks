# Домашнее задание к занятию «Компоненты персонажа»

### Цель задания

1. Расширить Animation Blueprint.
2. Потренироваться в настройке State Machine.
3. Поработать с Action Mappings.


### Инструкция по выполнению домашнего задания

Изучите дополнительные материалы к лекции из презентации.

------

### Задание 1 «Реализовать состояние спринта в С++»

Расширьте созданную <b>State Machine</b>, а именно реализуйте логику, при которой ваш персонаж будет спринтовать. Cоздайте ограничивающие условия, при которых игрок не может пользоваться спринтом. Последовательность действий ваша должна быть следующей:
* Создайте новое событие обработки вводимых данных Action Mappings. Назовите его Sprint.
* Восстановите переходы состояний в вашей State Mechine. Логика переключения состояний должна приходить от персонажа. 
* Добавьте необходимые переменные в файле LMADefaultCharacter.h
* Определите новые методы, восприятия входных данных.
* Определите новые переменные и методы ограничивающие условия запуска спринта. Реализуйте их путем внедрения локальной выносливости.
* Выносливость должна тратиться при спринте и восстанавливаться во время деактивации спринта.

У нас не большое количество анимаций, поэтому у нас может воспроизводиться спринт во время бега назад, вправо или влево, но в данном домашнем задании, самое главное – это создать инструмент который сможет переключать вашу <b>State Machine</b>. А также регулировать ее в зависимости от условий.

------

### Правила приёма домашней работы

Чтобы сдать домашнее задание, пришлите в личном кабинете удаленный репозиторий со своим проектом.

### Критерии оценки домашней работы

1. В личном кабинете прикреплена ссылка на удаленный репозиторий со своим проектом для задания 1.
2. Ваш персонаж осуществляет спринт при нажатии определенной кнопки, проигрывается анимация спринта, изменяется его скорость. 
3. Спринт деактивируется при отпускании кнопки, либо истощения выносливости, скорость возвращается к дефолтному состоянию, анимация возвращается в состояние Normal.
4. Выносливость восстанавливается до ограниченного значения в период неактивного спринта.

