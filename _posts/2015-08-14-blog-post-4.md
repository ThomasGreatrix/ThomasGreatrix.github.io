---
title: 'Infinite descent to show a diophantine equation has no solutions.'
date: 2015-08-14
permalink: /posts/2012/08/blog-post-4/
tags:
  - Number theory
---
This post serves to highlight a method of showing a method of showing a diophantine equation has no solutions. This method isn't very useful from a purely practical perspective, and will often break. Despite this, I find it an interesting approach nonetheless due to its use of infinite descent.

Consider the following equation:

\\[ 3x^3 + 2y^3 = 12z^3 \]]

The goal is to prove that this equation has no non-trivial solutions if we require \\( x,y,z \\) to all be integers. We will do so below.

Proof:
\\[ 3x^3 + 2y^3 = 12z^3\\]
\\[ \implies x is even. Let x = 2a: \\]
\\[ 3(2a)^3 + 2y^3 = 12z^3 \\]
\\[ 24a^3 + 2y^3 = 12z^3 \\]
\\[ 12a^3 + y^3 = 6z^3 \\]
\\[ \implies y is even. Let y = 2b: \\]
\\[ 12a^3 + (2b)^3 = 6z^3 \\]
\\[ 12a^3 + 8b^3 = 6z^3 \\]
\\[ 6a^3 + 4b^3 = 3z^3 \\]
\\[ \implies z is even. Let z = 2c: \\]
\\[ 6a^3 + 4b^3 = 3(2c)^3\\]
\\[ 6a^3 + 4b^3 = 24c^3 \\]
\\[ 3a^3 + 2b^3 = 12c^3 \\]

Note that the last equation here is the same as our initial one - except \\( x,y,z \\) has been replaced with \\( a,b,c \\). Hence, we can repeat this procedure infinitely each time getting closer to 0 - thus, by infinite descent, the equation must have no non-trivial solutions in the integers.
