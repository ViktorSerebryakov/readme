h1 Landings
===========

h2 Description
———————————-
Лэндинги выполнены в формате java server page (jsp),  и упакованы в war архив.


### h3 Installation

Для запуска лэндингов необходимо скачать apache tomcat,
 и закинуть .war архив в директорию tomcat/webapps.
Далее лэндинг можно открыть по адресу localhost:8080/landing/index.jsp
где /landing - это название .war архива. 

Для изменения лэндинга необходимо распаковать .war архив, открыть index.jsp в редакторе, внести изменения.
Запаковать в .war архив командой в консоли jar -cvf name.war * 