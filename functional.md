##Box
- known as the identity functor
- map just applies the provided function and returns it in a Box
- fold applies the function, but doesn't wrap it in a Box

##Semigroups
- a type with a concat method
- the concat is associative

##Monoid
- a Semigroup with a special element that acts as an identity (0)
- sum, product, any, all, max, min

##Functor
- any type with a map method with certain laws
- 1. map of f() and map of g() should be same as composing with map of f(g())
- 2. type.map(f) === f(type)

##Monad (of-able join-able, or unnestable, or of-able chain-able)
- has an of() (pure) and a chain() (flatMap, bind, >>=)
- like Box, Either, Task, List

- monad is a functor, and a pointed functor, and an applicative functor
