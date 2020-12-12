When requesting a new change for project, what's the difference between the stakeholders' point of view and the developer's one?

---

From the stakeholders’ point of view, they are simply providing a stream of
changes of roughly similar scope. From the developers’ point of view, the
stakeholders are giving them a stream of jigsaw puzzle pieces that they must
fit into a puzzle of ever-increasing complexity. Each new request is harder
to fit than the last, because the shape of the system does not match the shape
of the request. (that's why the system should be shape-agnostic)

===

Why a program that doesn't work but it's easy to change is sometimes much better than a program that works but it's impossible to change? (2)

---

-  If you give me a program that works perfectly but is impossible to change,
   then it won’t work when the requirements change, and I won’t be able to
   make it work. Therefore the program will become useless.
-  If you give me a program that does not work but is easy to change, then I
   can make it work, and keep it working as requirements change. Therefore
   the program will remain continually useful.

===

Acording to this list of priorities:

1. Urgent and important
2. Not urgent and important
3. Urgent and not important
4. Not urgent and not important

What's the mistake that business managers and developers often make?

---

The mistake that business managers and developers often make is to elevate
items in position 3 to position 1. In other words, they fail to separate those
features that are urgent but not important from those features that truly are
urgent and important. This failure then leads to ignoring the important
architecture of the system in favor of the unimportant features of the system.

===

Who's responsible to assert the importance of architecture over the urgency of features?

---

The dilemma for software developers is that business managers are not
equipped to evaluate the importance of architecture. That’s what software
developers were hired to do. Therefore it is the responsibility of the software
development team to assert the importance of architecture over the urgency
of features.
