# Position Size Calculator

Професионален **Forex Position Size Calculator** за правилно управление на риска.

## Какво прави?

Изчислява точния размер на позицията (lots), така че да рискуваш **точно** определения процент от акаунта си при достигане на Stop Loss.

### Основна формула

```
Risk Amount = Account Balance × (Risk % / 100)
Lots = Risk Amount ÷ (Stop Loss in pips × Pip Value per lot)
```

## Функции

- Баланс на акаунта
- Риск на сделка в %
- Stop Loss в пипсове
- Избор на валутна двойка (EURUSD, GBPUSD, USDJPY, XAUUSD и др.)
- Автоматично изчисление на Pip Value
- Take Profit + Risk:Reward ratio
- Поддръжка на Gold и Silver
- Мобилен дизайн (работи отлично на телефон)
- Изцяло на български

## Как да го пуснеш (GitHub Pages)

1. Качи файловете `index.html` и `README.md` в root на това repo
2. Отиди в **Settings → Pages**
3. Под "Source" избери **Deploy from a branch**
4. Branch: `main` / folder: `/ (root)`
5. Запази

След 1-2 минути сайтът ще е достъпен на:
**https://brokenboy1125.github.io/position-size-calculator/**

## Как да качиш файловете

### Вариант 1: През GitHub сайта (най-лесно)
1. Отвори repo-то
2. Натисни **Add file → Upload files**
3. Пусни `index.html` и `README.md`
4. Commit

### Вариант 2: През Git (ако ползваш)
```bash
git add index.html README.md
git commit -m "Add Position Size Calculator"
git push
```

## Препоръки за риск

| Риск на сделка | Ниво          | Коментар                          |
|----------------|---------------|-----------------------------------|
| 0.5%           | Консервативен | Добре за начинаещи                |
| 1%             | Стандарт      | Най-често използван от професионалисти |
| 2%             | Агресивен     | По-големи люлки                   |
| > 3%           | Опасно        | Висок риск от бърза загуба на акаунта |

---

**Важно:** Това е инструмент за образователни цели. Винаги проверявай спецификациите на брокера си (contract size, pip value, margin).
