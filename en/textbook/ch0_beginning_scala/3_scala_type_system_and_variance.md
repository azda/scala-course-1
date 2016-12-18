Система типов Scala
===================
Материалы данного раздела посвящены типам, и системе типов в `Scala`.
В качестве основного материала, можем вам порекомендовать
соответствующий раздел [Twitter Scala School][type-basics], а так же
статью [Scala's Types of types][types-of-types] (пожалуй самая мощная
из всех статей, посвященных системе типов `Scala`).

## Bounds
Если вы будете читать про Bounds, знайте, начиная с версии `2.11` они
объявлены устаревшими (deprecated). В `Dotty` их, например нет. Не
используйте Bounds, и не привыкайте. Об этом предупреждаем заранее. В
этой теме можно даже не разбираться.

## Вариантность
[Статья][variance], которая знакомит читателя с вариантностью типов в
`Scala`.

## Value types
также присутствуют в `Scala`, подробнее [здесь][value-types].

## Псевдонимы типов (Type aliases)
По возможности используйте псевдонимы типов, там где это возможно.
Это делает ваш код более читаемым, согласитесь что `Map[Username, Key]`
выглядит лучше, чем `Map[String, String]`.

[variance]: https://blog.codecentric.de/en/2015/03/scala-type-system-parameterized-types-variances-part-1/
[type-basics]: https://twitter.github.io/scala_school/type-basics.html
[types-of-types]: http://ktoso.github.io/scala-types-of-types/
[value-types]: http://docs.scala-lang.org/overviews/core/value-classes.html

