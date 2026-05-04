# Kerneu-K

Русская версия сайта энергетических услуг Kerneu-K на базе Jekyll Serif, подготовленная для публикации через GitHub Pages.

## Локальный запуск

```bash
bundle install
bundle exec jekyll serve
```

Сайт будет доступен локально по адресу, который покажет Jekyll. Для production-сборки:

```bash
bundle exec jekyll build
```

## Публикация

В репозитории есть GitHub Actions workflow `.github/workflows/pages.yml`. После push в `main` он собирает Jekyll и публикует сайт через GitHub Pages.

Тема основана на MIT-проекте [Jekyll Serif Theme](https://github.com/zerostaticthemes/jekyll-serif-theme) от Zerostatic.
