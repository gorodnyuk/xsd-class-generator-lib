Пример генерации dto из XSD.
Достаточно запустить команды mvn clean install для сборки библиотеки с готовыми dto.
Для генерации из нескольких схем необходимо создать <execution> для каждой схемы.

Существует проблема с плагином maven-surefire-plugin. Решение:
- Отключить его
- Запуск инсталяции через mvn clean install -DskipTests
