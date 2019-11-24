> Russian

История одного Франкенштейна


Пришёл к нам в компанию один клиент. Простой клиент. И сказал: "хочу PWA для своего сайта, но так чтобы можно было установить из Play Market и AppStore, а для устаревших устройств можно было смотреть из браузера". Главное условие - одна кодовая база для всех платформ.
Ранее в компании не было подобных проектов. Я искал готовые технологии и понял, что таких нет. Готовых решений нет. Что же делать?
Началось исследование. Я начал анализировать PWA и как его использования. Расскажу кратко что такое PWA. Это мобильное приложение, которое можно установить из браузера. Технология разработана компанией Google и запущена в 2017-ом году. По сей день технология является экспериментальной. Главная целью является повышение качества пользовательского опыта. Если пользователь ресурсом доволен, то он вернётся обратно. С технической стороны, такое приложение имеет очень много ограничений по сравнению с нативными приложениями. Дополнительной сложностью является политика безопасности iOS. На iOS доступно меньше функционала для PWA, чем на Android.

И тут мне пришла идея. Скомбинировать несколько технологий в одну. Так начал рождаться Франкенштейн. 
Я использовал технологию для создания одностраничных веб-приложений, технологию кросс-платформенной разработки мобильных приложений для iOS и Android, и один UI фреймворк. API для приложения предстояло писать на PHP.

Мне это удалось. Оно живёт! Мне удалось создать рабочую версию. Её можно установить на смартфон через браузер как PWA, через Play Market и AppStore, а также посмотреть через браузер. 

И тут выходит мажорное обновление для iOS. iOS 12. Обновление очень хорошее. Было. Самой большой неприятностью было изменение в политике безопасности. PWA для iOS стало вести себя не так как раньше. 
Самой очевидной проблемой стало HTTP-запросы. Фреймворк для кросс-платформенной мобильной разработки больше не мог работать с iOS так как раньше. Однако были и менее очевидные заметные проблемы. Для примера: баг третьего запуска. Называется так потому что PWA.iOS начинало работать так как надо только после третьего запуска.

Оставалось две недели до релиза. Пришлось перенести релиз. Я испробовал множество решений. Решение пришло мне в голову неожиданно. Была суббота. Половина третьего ночи. Я смотрел обзор на игру Doom Eternal. Оказалось что код для одного из экранов замораживался. Приложение оставалось на экране номер один в браузере, а установленная версия на экране номер четыре. Два одновременно работающих приложения в разных состояниях. Я создал синхронизацию между ними и оно начало работать так как нужно. Ура!

Через день приложение блокируется Play Market. Они решили, что это спам приложение. Play Market стал для нас потерян. 

В остальном, всё хорошо. Мы выпустили релиз и поддерживаем приложение. 


> English

The history of one Frankenstein

One client came to the company. The simple client. And says: "i want the PWA for my site but to be able to install from Play Market and AppStore, and for old devices to be able to see from browser". General condition - one codebase for all platforms.
In company earlier there was no such projects. I searched a ready technologies and understand that such no. The complete solution no. What to do?
The research began. I began analyzing the PWA and ways his using. I'll tell you what it is PWA. This is mobile application which can be install from browser. Technology is created by Google and launched in the seventeeth year. This is technology is experimental nowadays. The main goal is increase user experiance. If user happy of resource then he return to back. On the technical side such application have very much restrictions in comparison with native application. The additional complexity is the privacy policy of iOS. On the iOS available less functions for PWA in comparison with Android. 

And then I had an idea. Combine several technologies in one. So began to be bord Frankenstein.
I used technology for created single page application of web, the technology for cross-platform develop for iOS and Android, and one UI framework. The API for application had to write on PHP.

I succeeded. It lives! I created succeded the working version of app. It can be install on the smartphone through browser how PWA, through Play Market and AppStore, and watch through browser. 

And then major update coming out for iOS. iOS twelve. The update is very good. It was. Is very big trouble it was change in privacy policy. The PWA of iOS became behave not so as before. 
HTTP-requests become is very big problem. Framework for the cross-platform mobile develop couldn't work anymore with iOS as before. However there were less obviously problems. For example: the third bug run.
It is called so because PWA.iOS begun is working as it should be only as before third run.

There were two weeks to release. The release had to reschedule. I used very much solutions. The solution it occurred to me suddenly. This is was saturday. Half past two in the morning. I watched the review on the Doom Eternal game. It turned out that the code for one of them screens is freeze. Application is active remained on the firsrt screen and installed version on the fourth screen. Two simultaneously working application in the different state. I created synchronize between them and it began is working at is should. Hooray!

In a day Play Market blocks the app. They decided what this is spam application. Play Market is lost to us.

Everithing else is good. We released a release and support app.