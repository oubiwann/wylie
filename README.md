Extended Wylie Tibetan Script
=============================

EWTS UTF-8 Encoder.

Preparation
-----------

```bash
$ rebar compile
$ erl -pa ./ebin +pc unicode
```

Usage
-----

```erlang
1> wylie:tibetan("klong chen snying thig").
"ཀློང་ཆེན་སྙིང་ཐིག"
```

Credits
-------

* Namdak Tonpa

OM A HUM
