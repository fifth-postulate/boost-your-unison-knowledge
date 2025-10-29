# Origin
Let's talk about this workshop.

My first experiences with a computer where on a machine that had a
tape-recorder. When you invoked a magic incantation, the tape which contained
the game I want to play would whir and whine until the game could be started by
yet another arcane invocation.

While still young and walking through the local secondhand bookshop, I asked my
mother for a book about this mysterious machine: the Commodore 64.

The book explained a little bit of the machine and its language. It was BASIC,
just like my understanding of the subject matter.

## Modern Day Software Development
Modern day software development seems a far cry from my first experiences on
the Commodore.

We have version controlled source code, that often times build artifacts and
containers that run on clusters provisioned on machines that are not your own.

These towers of abstraction are impressive.

But they come at a downside. Network boundaries are often crossed, which incur
a cost because data often needs to be serialized to be send over the wire only
to be deserialized on the other side.
Or data is fetched from a database that needs help in describing all the
intricate details of the model, which is prone to various errors.
Or the deploymentis, which luckily are described in code, are nonetheless
written in a type-unsafe language, vastly differing from the one in which the
application is written.

It this the best we can do?

## Programming Language from the Future
[Unison][unison] a

> friendly programming language from the future:
> statically-typed, functional, and a lot of fun 😄 

improves on a lot of the above mentioned points. When I encountered it, I was
pleasantly surprised! There are a number of innovative features and concepts
that make it worthwhile to learn.
Learning about it more my mind was often blown, and it is this feeling that I
want to share with you.

I hope you will join me and explore this fun new way of developing software.
It is my pleasure to be your guide.

[unison]: https://www.unison-lang.org/
