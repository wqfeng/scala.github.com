---
layout: tutorial
title: 简介

disqus: true

tutorial: scala-tour
num: 1
outof: 33
tutorial-next: unified-types
---

Scala 是一门现代化的、多范式语言，用它编写的程序简洁、优雅、并且类型安全。它将面向对象和函数式编程融为一体。

## 面向对象的 Scala ##

Scala 里[一切皆对象](unified-types.html)，是一种纯面向对象的语言。[类](classes.html)和[traits](traits.html)描述了对象的类型和行为，子类扩展了父类的行为，[基于混入的组合](mixin-class-composition.html)机制干净漂亮地替代了多重继承。

## 函数式 Scala ##

Scala 里[函数都是值](unified-types.html)，是一门函数式编程语言。它提供了[简单的语法](anonymous-function-syntax.html)定义匿名函数，并支持[高阶函数](higher-order-functions.html)，它允许函数[嵌套](nested-functions.html)，还支持[柯里化](currying.html)。它的[case classes](case-classes.html)和对[模式匹配](pattern-matching.html)的内建支持，易于对数学运算建模，被很多函数式语言所采用。[Singleton objects](singleton-objects.html)可以方便地把不属于类的函数组织在一起。

Furthermore, Scala's notion of pattern matching naturally extends to the [processing of XML data](xml-processing.html) with the help of [right-ignoring sequence patterns](regular-expression-patterns.html), by way of general extension via [extractor objects](extractor-objects.html). In this context, [sequence comprehensions](sequence-comprehensions.html) are useful for formulating queries. These features make Scala ideal for developing applications like web services.

## Scala is statically typed ##
Scala is equipped with an expressive type system that enforces statically that abstractions are used in a safe and coherent manner. In particular, the type system supports:

* [generic classes](generic-classes.html)
* [variance annotations](variances.html)
* [upper](upper-type-bounds.html) and [lower](lower-type-bounds.html) type bounds,
* [inner classes](inner-classes.html) and [abstract types](abstract-types.html) as object members
* [compound types](compound-types.html)
* [explicitly typed self references](explicitly-typed-self-references.html)
* [implicit parameters](implicit-parameters.html) and [conversions](implicit-conversions.html)
* [polymorphic methods](polymorphic-methods.html)

A [local type inference mechanism](local-type-inference.html) takes care that the user is not required to annotate the program with redundant type information. In combination, these features provide a powerful basis for the safe reuse of programming abstractions and for the type-safe extension of software.

## Scala is extensible ##

In practice, the development of domain-specific applications often requires domain-specific language extensions. Scala provides a unique combination of language mechanisms that make it easy to smoothly add new language constructs in form of libraries:

* any method may be used as an [infix or postfix operator](operators.html)
* [closures are constructed automatically depending on the expected type](automatic-closures.html) (target typing).

A joint use of both features facilitates the definition of new statements without extending the syntax and without using macro-like meta-programming facilities.

Scala is designed to interoperate well with the popular Java 2 Runtime Environment (JRE). In particular, the interaction with the mainstream object-oriented Java programming language is as smooth as possible. Newer Java features like [annotations](annotations.html) and Java generics have direct analogues in Scala. Those Scala features without Java analogues, such as [default](default-parameter-values.html) and [named parameters](named-parameters.html), compile as close to Java as they can reasonably come. Scala has the same compilation model (separate compilation, dynamic class loading) like Java and allows access to thousands of existing high-quality libraries.

Please continue to the next page to read more.
