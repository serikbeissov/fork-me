# fork-me

Проект для изучения работы механизма `fork` в GitHub.

В файле [stepik-courses.sh](./stepik-courses.sh) содержится скрипт для получения списка курсов из платформы stepik.org.

### Ветки

- main
- dev

### Пример

Для запуска скрипты выполните команду.

```bash
./stepik-courses.sh
```

Вывод:

```
{
  "meta": {
    "page": 1,
    "has_next": true,
    "has_previous": false
  },
  "course-lists": [
    {
      "id": 1,
      "position": 1,
...
```
