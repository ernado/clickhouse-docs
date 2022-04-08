---
sidebar_position: 107
---

# corr {#corrx-y}

Синтаксис: `corr(x, y)`

Вычисляет коэффициент корреляции Пирсона: `Σ((x - x̅)(y - y̅)) / sqrt(Σ((x - x̅)^2) * Σ((y - y̅)^2))`.

    :::note "Примечание"
    Функция использует вычислительно неустойчивый алгоритм. Если для ваших расчётов необходима [вычислительная устойчивость](https://ru.wikipedia.org/wiki/Вычислительная_устойчивость), используйте функцию `corrStable`. Она работает медленнее, но обеспечивает меньшую вычислительную ошибку.
    :::