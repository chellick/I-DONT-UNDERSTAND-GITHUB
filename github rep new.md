# Словари в Питоне

Словари в Python - неупорядоченные коллекции произвольных объектов с доступом по ключу. Их иногда ещё называют ассоциативными массивами или хеш-таблицами.

Чтобы работать со словарём, его нужно создать. Сделать это можно несколькими способами. Во-первых, с помощью литерала:

```python
d = {}
d
{}
d = {'dict': 1, 'dictionary': 2}
d
{'dict': 1, 'dictionary': 2}
Во-вторых, с помощью функции dict:


d = dict(short='dict', long='dictionary')
d
{'short': 'dict', 'long': 'dictionary'}
d = dict([(1, 1), (2, 4)])
d
{1: 1, 2: 4}
В-третьих, с помощью метода fromkeys:


d = dict.fromkeys(['a', 'b'])
d
{'a': None, 'b': None}
d = dict.fromkeys(['a', 'b'], 100)
d
{'a': 100, 'b': 100}
```

Dict are:

- Nice
- Usefull
- Interesting

also:

- [ ] lol
- [ ] dont even care
- [ ] Petar Martich

new petar is ready

$$
\int_{}^{}\frac{dx}{a^{2}+x^{2}}=\frac{1}{a}\arctan\frac{x}{a}+C   (a\neq 0)
$$

$$
\int_{}^{}\frac{dx}{\sqrt{x^{2}\pm a^{2}}}=\ln\left| x+\sqrt{x^{2}\pm a^{2}} \right| + C(a > 0)
$$

$$
d*(f,g)= \int_{a}^{b}\left| f(t)-g(t)dt \right| <\delta
$$
