# Kerneu-K

Сайт услуг по энергетике на базе Jekyll Serif. Шаблон сохранён по структуре, контент переведён на русский и адаптирован под инженерные услуги Kerneu-K.

## Локальный запуск

```bash
bundle install
bundle exec jekyll serve
```

## Сборка

```bash
bundle exec jekyll build
```

## GitHub Pages

Публикация настроена через `.github/workflows/pages.yml`. После push в `main` GitHub Actions собирает Jekyll и выкладывает сайт на GitHub Pages.

Основано на MIT-теме [Jekyll Serif Theme](https://github.com/zerostaticthemes/jekyll-serif-theme).
