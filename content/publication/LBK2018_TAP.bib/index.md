+++
title = "Ghosts for Lists: from Axiomatic to Executable   Specifications"
date = 2018-01-01
authors = ["Frédéric Loulergue", "Allan Blanchard", "Nikolai Kosmatov"]
publication_types = ["1"]
abstract = "Internet of Things (IoT) applications are becoming   increasingly critical and require formal   verification.  Our recent work presented formal   verification of the linked list module of Contiki,   an OS for IoT. It relies on a parallel view of a   linked list via a companion ghost array and uses an   inductive predicate to link both views.  A few   interactively proved lemmas allow for an automatic   proof of other specifications, expressed in the ACSL   specification language and proved with the   Frama-C/WP tool.  In a broader verification context,   especially as long as the whole system is not yet   formally verified, it would be very useful to use   runtime verification, in particular, to test client   modules that use the list module.  It is not   possible with the current specifications, which   include an inductive predicate and axiomatically   defined functions.  In this early-idea paper we show   how to define a provably equivalent non-inductive   predicate and a provably equivalent non-axiomatic   function that belong to the executable subset eacsl   of ACSL and can be transformed into executable C   code.  Finally, we propose an extension of Frama-C   to handle both axiomatic specifications for   deductive verification and executable specifications   for runtime verification."
selected = "false"
publication = "*Tests and Proofs (TAP)*"
doi = "10.1007/978-3-319-92994-1_11"
+++
