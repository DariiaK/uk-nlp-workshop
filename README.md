## Воркшоп з комп'ютерної лінгвістики від Grammarly

**Кому буде цікаво:** студентам-лінгвістам, які хочуть навчитися автоматичного опрацювання мови.

### Програма воркшопу

1. Лекція "Комп'ютерна лінгвістика як професія"
   * Які завдання вирішують комп'ютерні лінгвісти?
   * Які навички потрібні для роботи в компанії?
   * Як потрапити на літню школу з комп’ютерної лінгвістики?

2. Практичне заняття "Автоматичне опрацювання української мови"
   * Як користуватися бібліотеками з опрацювання природної мови?
   * Як робити частотний аналіз на основі корпусів текстів?
   * Як працювати з деревами залежностей?

### Програмне забезпечення для практичного заняття

1. Перевірте, що у вас встановлений Python 3 та ваше улюблене середовище для розробки (PyCharm, Sublime, PyDev, IDLE тощо).
2. Запустіть програму командного рядка. Це може бути Terminal (якщо у вас Mac OS), Shell (якщо у вас Linux) чи Windows command prompt (якщо у вас Windows).
3. Встановіть [токенізатор для української мови](https://github.com/lang-uk/tokenize-uk), виконавши таку команду в командному рядку:
   ```
   pip install tokenize_uk
   ```
4. Встановіть [Git](https://git-scm.com/).
5. Встановіть бібліотеку для морфологічного аналізу [pymorphy2](https://github.com/kmike/pymorphy2) з підтримкою української мови, виконавши таку команду в командному рядку:
   ```
   pip install git+https://github.com/kmike/pymorphy2.git pymorphy2-dicts-uk
   ```

**Дані** для практичного заняття потрібно завантажити із теки [data/](data).

### Де знайти дані та інструменти для роботи з українською мовою

1. Бібліотека [lang-uk](https://lang.org.ua/en/) містить інструменти для токенізації та визначення іменованих сутностей, а також корпуси українськомовних текстів.
2. Репозиторій [brown-uk](https://github.com/brown-uk/) містить Браунський корпус української мови та граматичний словник на 3,5 млн словоформ.
3. Бібліотека [pymorphy2](https://github.com/kmike/pymorphy2) надає морфологічний аналіз словоформ української мови, використовуючи вищезгаданий словник.
4. Бібліотека [StanfordNLP](https://stanfordnlp.github.io/stanfordnlp/) надає моделі для токенізації, лематизації, частиномовного аналізу та синтаксичного аналізу української мови.
5. Репозиторій [UD_Ukrainian-IU](https://github.com/UniversalDependencies/UD_Ukrainian-IU/tree/master) містить корпус дерев залежностей для української мови. Цей корпус було використано для побудови моделей у вищезгаданій бібліотеці StanfordNLP.
