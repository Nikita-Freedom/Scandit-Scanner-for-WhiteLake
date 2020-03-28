# WhiteLakeProvider

Данное расширение для ОС Android,  позволяет сканировать штрих-код с помощью Scandit и отправлять результаты сканирования в любое приложение на смартфоне.

## Приступим

Данная инструкция поможет вам развернуть свой локальный сервер на виртуальной машине для хранения данных, загрузить и установить на телефон под операционной системой Android проводник для файлов, который поможет смотреть, открывать, скачивать файлы с тестового сервера(хранилища).

### Что нужно для работы?

Перед началом работы вам необходимо установить следующие компоненты: 
 1.Java SE Development Kit 8(понадобится для android studio). Установить можно с сайта:  https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

 2.Android Studio последней версии. Можно скачать с официального сайта:https://developer.android.com/studio
 Пройти весь процесс установки(в том числе загрузить SDK), загрузить виртуальный девайс для проверки расширения на нем.
 
 3.Пакет SDK (https://ssl.scandit.com/sdk/download/scandit-datacapture-android-6.2.0.zip)
 
 ### Шаги для установки apk
Как только вы убедились, что у вас установлена и корректно работает Android studio, подключен либо виртуальный девайс, либо реальное android устройство переходите к следующим действиям:
1. Скачайте отправленный вам на почту архив с APK. 
2. Распкакуйте в указанную вами папку.
3. Зайдите в Android studio и нажмите "Open an existing Android Studio project" как показано на скриншоте

![Image alt](https://github.com/Nikita-Freedom/WhiteLakeProvider/blob/master/1.jpg)

4. Найдите в списке файлов ваш распакованный APK

![Image alt](https://github.com/Nikita-Freedom/WhiteLakeProvider/blob/master/2.jpg)

5. Откройте ваш проект(APK) и дождитесь пока система сборки Gradle соберет ваш проект

![Image alt](https://github.com/Nikita-Freedom/WhiteLakeProvider/blob/master/3.jpg)

6. Как только система сборки соберет ваш проект выберите в панели сверху справа девайс на котором будет устанавливаться APK(это может быть как виртуальный девайс, так и реальное Android устройство, подключенное к компьютеру с включенным режимом отладки)

![Image alt](https://github.com/Nikita-Freedom/WhiteLakeProvider/blob/master/5.jpg)

7. Как только проект будет собран, нажмите зеленую стрелочку(кнопку Run) на верхней панели справа

![Image alt](https://github.com/Nikita-Freedom/WhiteLakeProvider/blob/master/4.jpg)

8. Дождитесь установки APK на ваш девайс.

9. После установки приложения на телефон у вас откроется окно с вводом сервера и кнопкой под ним "сканировать штрихкод". Нажмите на эту кнопку.

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scannerSCAN.png)

10. При нажатии на кнопку открывается окно с запросом на разрешение пользоваяни камерой. 

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scan2.jpg)

11. Нажмите разрешить. Перед вами будет окно с камерой и двумя кнопками снизу. Наведите камеру на штрихкод чтобы считыватель смог отсканировать его.

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scan3.jpg)

12. Нажмите кнопку "сканировать штрихкод". Перед вами появится активность с результатом сканирования. Сам штрихкод и его тип.

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scan4.jpg)

13. При нажатии на кнопку "поделиться" вы можете отправить результат сканирования в текстовом виде в любое приложение на смартфоне. В примере мы отправляем в сообщениях.

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scan5.jpg)

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scan6.jpg)

14. Также в окне сканирования есть вторая кнопка, которая позволяет сорхранить штрихкод в файловое хранилище на телефоне(SD Card). Внизу можно увидеть путь, куда сохраняется изображение.

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scan7jpg)

15. Также сканер умеет сканировать сразу несколько штрих-кодов одновременно и выводить результаты на экран.

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scan8.jpg)

![Image alt](https://github.com/Nikita-Freedom/Scandit-Scanner-for-WhiteLake/blob/master/scan9.jpg)
## Построен с помощью

* [Scandit SDK](https://www.scandit.com/) - Используется Scandit для генерации штрихкодов.
* [Maven](https://maven.apache.org/) - Зависимость
* [ShareSheet Android](https://developer.android.com/training/sharing/send) - Используется для отправки результата сканирования в любое приложение.

## Автор

* **Ульянов Никита**  [Nikita-Freedom](https://github.com/Nikita-Freedom)

## Подтверждения

* Предназначено для компании WhiteLake
