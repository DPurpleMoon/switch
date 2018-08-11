---
permalink: /faq.html
title: Часто задаваемые вопросы
author_profile: true
---
{% include toc title="Разделы" %}

## Общие сведения

### **В:** Мой свитч имеет прошивку версии X.X.X, смогу ли я его прошить?
**О:** Да. В данный момент прошиваются все консоли, которые можно купить в европейских и американских магазинах 

### **В:** Нужно ли мне что-либо паять для использования взлома?
**О:** Нет

### **В:** Что нужно для использования взлома? 
**О:** Сам свитч, карта памяти, скрепка и хост-устройство (ПК/Android/iOS с джейлбрейком/донгл) для [запуска взлома](fusee-gelee){:target="_blank"}

### **В:** Смогу ли я устанавливать цифровые релизы? 
**О:** Да

### **В:** В Homebrew Menu нет ни одного приложения, хотя на карте они есть
**О:** Снимите архивный атрибут у файлов. 

### **В:** Возникают ошибки при установке NSP-файлов 
**О:** Дайте файлом короткое имя. Если не помогло - перекачайте файлы, возможно они не докачаны

### **В:** Смогу ли я после взлома запускать сторонние программы и эмуляторы?
**О:** Да! Кастомная прошивка поддерживает Homebrew Launcher. Причем пользоваться Homebrew Launcher можно и на SX OS by Team Xecuter без покупки лицензии.

### **В:** Поддерживает switch флеш карты отформатированные в exFAT?
**О:** exFAT поддерживается на прошивках выше 4.1.0. Однако для этого придется качать обновление, или [патчить прошивку](https://vk.com/@switchbreak-exfat-support){:target="_blank"}

### **В:** Как мне перенести данные на новую SD-карту?
**О:** Просто скопируйте все файлы на новую SD-карту.

### **В:** Можно ли запускать игры другого региона?
**О:** Да, можно.

### **В:** Можно ли перенести дамп NAND с одной системы на другую?
**О:** NAND шифруется уникальным для каждой консоли ключом, поэтому перенос невозможен.

### **В:** Могу ли я обойтись без использования компьютера (например, использовать телефон на Android)?
**О:** Инжект пейлоада можно производить с помощью ПК, Android или специальных донглов (SX PRO).

### **В:** Можно ли играть онлайн? 
**О:** Нет - забанят

### **В:** Что по поводу банов?
**О:** За взлом вас могут забанить в любой момент. Надёжного способа избежать бана нет. Надёжнее всего пользоваться взломом, полностью отключив на приставке интернет, а потом, при желании вернуться на официальную прошивку, или при желании включить интернет - восстановить бекап, который был сделан до запуска чего-либо пиратского. В целом же ситуация такая - если вы не готовы попасть в бан и лишиться онлайна - откажитесь от пиратства! И да, вас могут забанить даже за использование HBL, если вы будете использовать интернет. Еще раз - перед использованием интернета, даже если вы просто запускали HBL, обязательно восстановите бекап, на котором всё без палева!

### **В:** Чего я лишусь в случае бана? 
**О:** Бан может быть разным: на картридж, на аккаунт или целиком на консоль. В самом плохом случае Вы теряете доступ к eShop и онлайн сервису соответственно, при этом системное ПО и обновления игр будут качаться.

### **В:** Какого размера карта рекомендуется? 
**О:** Я бы брал не менее 64Гб. Чем больше карта, тем больше игр влезет

### **В:** Это всё бесплатно?
**О:** В базовом виде - да. Но если хотите простоты и комфорта - придётся купить [SX OS](sxos){:target="_blank"} или [SX OS Pro](sxos){:target="_blank"}. Однако, на пятки SX OS наступает [ReiNX](reinx){:target="_blank"}, которая уже может устанавливать и запускать игры совершенно бесплатно. 

### **В:** Каков шанс брика? 
**О:** Зависит от того, как чётко вы следуете инструкциям. Обязательно сделайте [бекап](backup-nand){:target="_blank"}! 

### **В:** Homebrew Launcher не видит скачанные .nro файлы 
**О:** 

* Если у вас Mac, то после скачки всех файлов на карту памяти, необходимо в терминале прописать следующую команду:

	* `sudo chflags -R arch /Volumes/SDNAME`, где SDNAME - название вашей карты памяти.
	
* Если у вас Win, то необходимо снять архивные атрибуты с файлов на карте памяти (в первую очередь с файлов в папке switch).Правая кнопка мыши -> свойства.
* Или на самом switch'е через hekate (во вкладке tools есть соответствующая опция).

## SX OS

### **В:** Что это вообще такое?
**О:** [SX OS](sxos){:target="_blank"}

### **В:** Как запускать игры при помощи SX OS?
**О:** [Запуск игр](sxos-games){:target="_blank"}

### **В:** Можно ли запускать игры при помощи не активированной SX OS?
**О:** Нет. Бесплатно при помощи SX OS можно запустить только Homebrew Launcher.

### **В:** Как обновить SX OS?
**О:** Для обновления достаточно заменить файл boot.dat на карте памяти и перезапустить взлом через RMC.

### **В:** Игры не отображаются в альбоме.
**О:** Убедитесь, что образы в формате .xci лежат в корне карты памяти. Так же, если у вас последняя версия прошивки, убедитесь, что ваша карта памяти отформатирована в exFat.

### **В:** Ошибка при монтировании образа "Не удалось считать данные с игровой карты" .
**О:** Возможно нерабочий образ либо проблемы с картой памяти. Так же, если используете Mac для копирования образов, то попробуйте сделать это через Win.