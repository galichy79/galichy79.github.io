# Yu Blog

Персональный блог на Jekyll.

## Запуск локально

1. Установите Jekyll:
```bash
gem install --user-install jekyll bundler
```

2. Запустите сервер:
```bash
export PATH="$PATH:/home/u/.local/share/gem/ruby/3.2.0/bin" && jekyll serve --host 0.0.0.0 --port 4000
```

3. Откройте в браузере: http://localhost:4000

## Остановка сервера

```bash
pkill -f jekyll
```

## Структура

- `_posts/` - статьи блога
- `_layouts/` - шаблоны страниц
- `_includes/` - переиспользуемые компоненты
- `css/` - стили
- `img/` - изображения

## Автор

Yu (galichy79@gmail.com)