---
uid: philipdexter
date: 2016-06-27
enddate: 2016-07-03
week: 27
generator: furore
---

This week I have generalized the perforation system to the point where I was able to take an off-the-shelf ocaml implementation of kmeans clustering and run it through the perforation system. The program was able to produce nice, readable results for different configurations [attached image]. However when more than 2 loops are perforated, the data starts becoming very hard to visualize. The system is really smooth but it's still lacking: I had to turn one use of List.iter into a for loop. However, I have created a plan to perforate recursive functions which will allow the system to work on programs which don't use for loops.

This week I also worked with the reagents library for ocaml-multicore. In the beginning of the week I parallelized an existing ray tracer written in OCaml. (The ray tracer also is a good candidate for perforation.) Further, KC and I have discussed working on a lock-free hash table implementation to use in the Hack type checker (written in OCaml). Currently hack use a C hash table implementation strapped on the to OCaml code. Writing a competitive implementation in OCaml would be a great way to show of ocaml-multicore.

