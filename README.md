Согласно условию домашнего задания созданы 2 отдельных workflow:

```
Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

Open -> On reproduce.
On reproduce -> Open, Done reproduce.
Done reproduce -> On fix.
On fix -> On reproduce, Done fix.
Done fix -> On test.
On test -> On fix, Done.
Done -> Closed, Open.

Остальные задачи должны проходить по упрощённому workflow:

Open -> On develop.
On develop -> Open, Done develop.
Done develop -> On test.
On test -> On develop, Done.
Done -> Closed, Open.

```

Схема workflow для типов задач `bug` выглядит следующим образом:
![image](https://github.com/shoonia69/ci/assets/102481493/4aaef093-009e-4bf3-92ad-64454a0d1bfe)

Схема workflow для типов задач `epic, task, story` выглядит следующим образом:
![image](https://github.com/shoonia69/ci/assets/102481493/020025c0-9c14-4958-8ec7-3d861d7c46d8)


