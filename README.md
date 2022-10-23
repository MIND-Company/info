![Header](https://user-images.githubusercontent.com/57585370/118307531-4231f900-b504-11eb-8106-061b97776823.png)
# Умная парковочная система
## Содержание
1. [Общая информация](#generalInfo)
2. [Сервер](#server)
3. [Веб-приложение для водителя](#driverWeb)
4. [Веб-приложение для владельца паркинга](#ownerWeb)
5. [UI библиотека](#uiLibrary)
6. [Сервер распознавания номеров](#recognize)
## Общая информация <a name="generalInfo" />
- Название проекта: **Smart Parking System** 
- Название команды: **M.I.N.D** 
- Участники команды:

| ФИО | Почта | Telegram | Github |
| ------------- | ------------- | ------------- | ------------- |
| Ермолаев Илья Дмитриевич | Ermolaev.ID@yandex.ru | [@Ermolaev_Ilya](https://t.me/ermolaev_ilya) | [Ссылка](https://github.com/ErmolaevID) |
| Колтунов Матвей Максимович | Koltunov.matwei@gmail.com | [@Koltunov_Matthew](https://t.me/Koltunov_Matthew) | [Ссылка](https://github.com/echanatwell) |
| Коробицын Дмитрий Кириллович | dimakorobitcyn@yandex.ru | [@magistrkanistr](https://t.me/magistrkanistr) | [Ссылка](https://github.com/FireFace1337) |
| Непочатый Никита Владимирович | nick.nnepochatyy@mail.ru | [@DefinitelyNik](https://t.me/DefinitelyNik) | [Ссылка](https://github.com/Nikegdo) |
| Пермяков Роман Александрович | roman.teckk@gmail.com | [@PermiakovRoman](https://t.me/PermiakovRoman) | [Ссылка](https://github.com/Buskervil) |

- Цель проекта: <br/>
Создать конкурентоспособную, прибыльную и удобную для пользователей модель автоматизированной парковочной системы.
- Описание: <br/>
Камера на въезде и выезде будет считывать номера автомобилей и отправлять запрос на сервер. Сервер, в свою очередь, будет регистрировать 
время въезда, выезда и рассчитывать стоимость паркинга. Если пользователь зарегистрировался в нашем приложении и привязал карту, то деньги
будут списываться автоматически. Если пользователь не зарегистрирован, то парковку можно оплатить через терминал на выезде. В связи с такой
автоматизацией, мы отказываемся от шлагбаумов. Пользователь просто заезжает и выезжает, не более.
- Целевая аудитория: <br/>
Для продажи нашей системы подходит абсолютно любая парковка; <br/>
Использовать нашу систему может абсолютной любой человек, имеющий транспортное средство и использующий парковку.
- Основное преимущество: <br/>
От пользователя парковки не требуется никаких действий. На въезде ему не нужно думать о том, как работает эта парковочная система, где 
нужно будет оплатить парковку, а также как не потерять карточку, которую ему сейчас выдаст терминал. Ему не нужно открывать окно, чтобы дотянуться
рукой до кнопки на терминале, не нужно выходить из машины, если он не дотягивается. А на выезде ему не нужно разбираться с оплатой. 
Пользователь просто заезжает и выезжает, думая о своих делах, а не о парковочной системе. Полная автоматизация, которая сделает пребывание
человека комфортным и удобным.

## Сервер <a name="server" />
Сервер - мозг нашей системы. Он обрабатывает всю информацию. Взаимодействует с камерами на паркинге, проводит оплаты, выдает информацию о водителях 
и владельцах паркинга. <br/>

Репозиторий: https://github.com/MIND-Company/api <br/>

## Веб-приложение для водителя <a name="driverWeb" />
Приложение через которое пользователь взаимодействует с нашей системой. Водитель может видеть свои паркинги, добавить способ оплаты. <br/>

Репозиторий: https://github.com/MIND-Company/client-web <br/>
Репозиторий мобильного приложения: https://github.com/MIND-Company/client-mobile <br/>

## Веб-приложение для владельца паркинга <a name="ownerWeb" />
В этом приложении владелец паркинга может зарегистрировать свой паркинг, следить за состоянием текущих паркингов. <br/>

Репозиторий: https://github.com/MIND-Company/owner-web <br/>

## UI бибилотека <a name="uiLibrary" />
Наша личная UI библиотека компонентов, которые используются в наших продуктах. <br/>

Репозиторий: https://github.com/MIND-Company/mind-ui <br/>
Storybook: https://mind-company.github.io/mind-ui/?path=/story/docs-hello--page <br/>
