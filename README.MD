Результат: новый репозиторий, один Пул Реквест!

1. Возвращать содержимое файла с python пакетами (requirements.txt) PATH: /requirements/ открыть файл requirements.txt и вернуть его содержимое

2. Вывести 100 случайно сгенерированных юзеров (почта + имя) 'Dmytro aasdasda@mail.com' PATH: /generate-users/ ( https://pypi.org/project/Faker/ ) + GET параметр который регулирует количество юзеров

3. Средний рост, средний вес (см, кг) (hw.csv) PATH: /mean/

4. Вывести количество космонавтов в настоящий момент ( http://api.open-notify.org/astros.json ) ( https://pypi.org/project/requests/ ) PATH: /space/

Пример запроса на сторонний API
import requests
r = requests.get('https://api.github.com/repos/psf/requests')
r.json()["description"]

P.S. не забывайте про .gitignore