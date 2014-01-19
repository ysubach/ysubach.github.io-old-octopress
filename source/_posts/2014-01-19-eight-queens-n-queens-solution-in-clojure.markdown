---
layout: post
title: "Eight queens (N-queens) solution in Clojure"
date: 2014-01-19 13:15
comments: true
categories: [fp, clojure] 
---
I have been interested in learning functional programming language 
during last months. My current choice is [Clojure](http://clojure.org/)
language because this is a dialect of List based on JVM. So it seems to
be good candidate for usage in real projects. 

Since functional programming requires thinking style
diffent from imperative languages like PHP, Python or Java I decided to
try and implement some pure computational task.

"Eight queens" task is perfect for testing functional programming
language because solution for this task is recursive. You need to put 8
queens on the chessboard so that no two queens attack each other. This
task can be extended to N-sized chessboard, in this case you need to
place N queens.

My solution in Clojure is written below:
{% gist 8503969 %}
