---
layout: post
title: "This is a title"
tags:
---

# Wrting a blog post from a iPad

Post is directly pushed to GitHub. 

```scala
// here some Scala code
case class Person(name: String, age: Int)

def receive: Receive = {
	case Person(name, age) if age >= 18 => println(s"$name is an adult")
	case Person(name, _) => println(s"$name is a child")
}