# soap-api-company-employee-tests

Запускаем автоматизированные SOAP API тесты (предаврительно должен быть установлен maven последней версии http://maven.apache.org/download.cgi, в переменную окружения PATH должен быть добавлен путь до mvn.bat):

* Если имеется лиценизия на ready-api https://smartbear.com/product/ready-api/overview/ (возможно временную) то переходим в директорию ready-api и запускаем mvn test
* Если лиценизии на ready-api нет то переходим в директорию soap-ui и запускаем mvn test

По смыслу проекты (CSSSR-Test-project-1-readyapi-project.xml  и CSSSR-Test-project-1-soapui-project.xml) с тестами почти одинаковые, но на ready-api проверки и работа с данными сделана более удобно из-за более расширенных возможностей ready-api.

Информация о статусе выполняемых тестов будет доступна в процессе запуска, а также target\surefire-reports\index.html. Например:

http://joxi.ru/L21JL60hRkpwPA
http://joxi.ru/GrqBMjLf4BjbNm

Сами файлы с проектами CSSSR-Test-project-1-readyapi-project.xml  и CSSSR-Test-project-1-soapui-project.xml создавались в Ready-Api-2.8.2 и SOAP-UI версии 5.5.0. Соответственно рекомендуется открывать и анализировать их содержимое именно в этих версиях.
