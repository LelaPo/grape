# grape

> **g**rape **r**escues **a**verages & **p**redicts **e**verything

<p align="left">
  <img src="https://img.shields.io/badge/размер-~15_кб-brightgreen?style=flat-square" alt="size" />
  <img src="https://img.shields.io/badge/зависимости-0-blue?style=flat-square" alt="dependencies" />
  <img src="https://img.shields.io/badge/стек-vanilla_js-yellow?style=flat-square" alt="stack" />
  <img src="https://img.shields.io/badge/лицензия-MIT-lightgrey?style=flat-square" alt="license" />
</p>

легковесный, моментальный инструмент для расчета и спасения средневзвешенного балла в школе.

**демо:** [https://lelapo.github.io/grape/](https://lelapo.github.io/grape/)

---

### возможности

* **ввод в 2 тапа:** быстрый выбор оценки и веса (д/з, самостоялка, контрольная, впр)
* **умный прогноз:** считает, сколько оценок нужно получить до желаемого балла (до 3, 4 или 5) с возможностью выбора, чем добивать
* **минималистичная лента:** аккуратные карточки оценок с весом работы, удаление по тапу
* **темы:** переключение на тёмную и светлую тему с сохранением в памяти
* **автосохранение:** не сбрасывает данные при обновлении страницы (`localstorage`)
* **0 оверхеда:** чистый html/css/js без сборщиков, библиотек и сторонних запросов

### запуск локально

никаких `npm install` не требуется. просто скачайте и запустите:

```bash
git clone https://github.com/LelaPo/grape.git
cd grape
open index.html
```

### лицензия

[mit](LICENSE)