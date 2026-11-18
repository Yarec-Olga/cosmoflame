# CosmoFlame

*[English](#english) | [Русский](#на-русском)*

## English

A text-based space adventure game written in Python. This is my first game,
built while working through Exercise 36 of Zed Shaw's *Learn Python the Hard Way*.

> **Note:** the in-game text is in Russian.

### Story

You are the captain of the experimental starship *CosmoFlame*. You once served
the Empire, but after being ordered to destroy a colony on the planet Tarron,
you stole the ship and disappeared. For three years you have worked alone…
until a distress signal breaks the silence.

Your choices decide who becomes your ally (the Traders, the Pirates, or no one)
and how the war against the Empire ends.

### Features

- 8 scenes with multiple-choice decisions
- experience points (XP) and levels
- credits (CR) and ship repairs
- ship hull integrity: if it drops to zero and you can't afford repairs, the game is over
- allies that change the course of the story
- random outcomes for some decisions
- multiple endings

### What I practiced

- functions and splitting a program into scenes
- dictionaries for storing the player's state
- `if` / `elif` / `else` branching
- `while` loops for validating user input
- the `random` module

### How to run

Requires [Python 3](https://www.python.org/downloads/).

```bash
python main.py
```

Enter your captain's name, then make choices by typing 1, 2 or 3.

---

## На русском

Текстовая игра-приключение в космосе на Python. Моя первая игра, написанная
по упражнению 36 из книги Зеда Шоу «Learn Python the Hard Way».

### Сюжет

Ты — капитан экспериментального корабля «CosmoFlame». Когда-то ты служил
Империи, но после приказа уничтожить колонию на планете Tarron украл корабль
и исчез. Три года ты работаешь один… пока в эфире не раздаётся сигнал о помощи.

Твои решения определяют, с кем ты окажешься в союзе — с Торговцами, Пиратами
или ни с кем, — и чем закончится война с Империей.

### Что есть в игре

- 8 сцен с выбором вариантов
- опыт (XP) и уровни
- кредиты (CR) и ремонт корабля
- прочность корабля — если она упадёт до нуля и не хватит денег на ремонт, игра окончена
- союзники, от которых зависит ход истории
- элемент случайности в некоторых решениях
- несколько концовок

### Как запустить

Нужен установленный [Python 3](https://www.python.org/downloads/).

```bash
python main.py
```

Введи имя капитана и выбирай варианты, набирая цифры 1, 2 или 3.
