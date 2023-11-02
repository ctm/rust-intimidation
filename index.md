---
title: Don't Be Intimidated (too much) Learn Rust
description: Why you may want to learn rust now
author: Cliff Matthews <clifford.t.matthews@gmail.com>
---
# Who am I?

* [Then](https://www.youtube.com/watch?v=ZQvEkVbisr0): [Executor](https://archive.org/details/executor) (C, Objective-C)
* In between I was a Ruby on Rails contractor and founded RubiABQ (RIP)
* [Now](https://www.youtube.com/watch?v=bXeDRbJP_QE): [craftpoker.com](https://craftpoker.com): (Rust)
---
Executive Summary:
> Don't let perfect be the enemy of good
---
This _not_ an attempt to convince you that:
* Rust is the best language
* Rust is better than "your" language
*  Rust is appropriate for the problems you work on

For me, an "old" guy with CRS, Rust:
* allows _me_ to build complex software
* is fun
* supports [belligerent refactoring](https://this-week-in-rust.org/blog/2020/06/02/this-week-in-rust-341/#quote-of-the-week)
* will allow others to come up to speed (I believe)
---
Languages
* Imperative: do this
* Functional: is this
* Rust: both plus "controlled memory management"
  * immutable by default
  * no dangling pointers
  * no use after free
  * no **data** races
---
What's so intimidating?
  * Ownership (enforced by the borrow checker)
  * Lifetimes
  * Macros
  * Trait objects
  * Really talented humble people
    * [Victor Wooten](https://www.youtube.com/watch?v=zjkFJkbm3vA)
    * [BurntSushi](https://blog.burntsushi.net/) author of&mdash;among others&mdash;[ripgrep](https://github.com/BurntSushi)
---
How to get started?

[https://rust-lang.org](https://www.rust-lang.org/) has plenty of material and links.
They're "Get started with Rust" portion of their [Learn Rust](https://www.rust-lang.org/learn) page includes links to:
* [The Rust Programming Language](https://doc.rust-lang.org/book/)
* [The Rustlings Course](https://github.com/rust-lang/rustlings/)
* [Rust by Example](https://doc.rust-lang.org/rust-by-example/)

You don't even need to install Rust to practice it using [practice.rs](https://practice.rs)

These reduce the macro and lifetime pain points:
* [macrokata](https://github.com/tfpk/macrokata)
* [lifetimekata](https://github.com/tfpk/lifetimekata)
---
How did I get started?

* [The Rust Programming Language](https://doc.rust-lang.org/book/)
* [This Week in Rust](https://this-week-in-rust.org/) (but&hellip; but&hellip; it's intimidating)
* I wrote [eus](https://github.com/ctm/eus), first in Ruby, then rewrote it in Rust
* I started using Rust for my little pet projects
  * I use [nom-fun](https://github.com/ctm/nom_fun) to extract running intervals
  * [digital-duration-nom](https://github.com/ctm/digital-duration-nom/blob/master/src/duration.rs) is a library to parse durations
  * [fantoccini-shiprock](https://github.com/ctm/fantoccini-shiprock) is a web scraper for various running results
  * [runs](https://github.com/ctm/runs) generates stats using scraped running results
___
Let's play and/or Q&A
___
Thank You

[Cliff Matthews](https://www.youtube.com/watch?v=B194kgpytOE&t=458s) &lt;[clifford.t.matthews@gmail.com](mailto:clifford.t.matthews@gmail.com)&gt;
aka [Young Lazy Deadhead](https://ctm.github.io/docs/yld/life/too-public.html)
