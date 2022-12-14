---
layout: "layouts/PageLayout.astro"
title: "Налаштування стрічки"
description: "Документ описує опції налаштування Стрічки"
---

Налаштування стрічки доступне тільки для авторизованих користувачів.

Користувач може відредагувати наступні опції:

- Мінімальний рейтінг поста
- Сортування Підписок за замовчуванням
- Відображення контента для дорослих

## Мінімальний рейтинг поста

Використовується у [ранжуванні постів](/feed/ranking).

Поле має тип `range` з єдиним значенням. Значення це число від `-10` до `10`.

## Сортування Підписок за замовчуванням

Використовується у [ранжуванні постів](/feed/ranking).

Поле має тип `select` з єдиним значенням. Значення це один з варіантів:

- `published` - сортування за датою поста
- `score` - сортування за рейтингом поста

## Відображення контента для дорослих

Поле має тип `select` з єдиним значенням. Значення це один з варіантів:

- `show` - показувати контент для дорослих
- `hide` - зкривати контент для дорослих
