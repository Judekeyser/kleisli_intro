# Introduction to Kleisli Category, for the programmer

Introduction to Kleisli Category for the programmer.

I do not allow reproduction of any kind, of the present repository nor of its content.
Material therein must be fairly well-known in the field of Category Theory, at least at the level of folklore.
(If not, it is sufficiently trivial to be so; there is nothing to steal here.)

The text is born, following a lot of discussions with programmers and their difficulty to grasp
the formal concept and intuition behind monad. After reading some books (especially Milewski's work), I found
the standard introductions to the topic were very abstract and no real motivation was given for the notion of `flatMap`.
The notion of Kleisli Category, although equivalent (as it seems), is usually introduced via even more difficult use cases.

Furthermore, most of the literature is written in Haskell, which definitly doesn't enjoy a very large audiance, eventhough the
concept of monads becomes more and more spread.

This text introduces monads with Java (a possibility was Python, but I kept Java for the ridig explicit static typing, so that
the reader can really feel what's going on (types as documentation)) and exclusively through the concept of Kleisli Category.
Actually, we introduce all the Category Theory via this motivation.

We largely come back to classic constructions: Option, Future, Iterator, ... and we discuss filtering.
