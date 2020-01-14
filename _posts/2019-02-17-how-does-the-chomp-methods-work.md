---
title: "TIL: How does .chomp method works?"
layout: post
date: 2019-02-17 20:44
image: /assets/images/markdown.jpg
headerImage: false
tag:
- programação
- ruby
star: true
category: blog
author: olimpio
description: Actually, what chomp does, is removing the Enter character at the end of your string
---

As I'm learning Ruby on [Codecademy](https://www.codecademy.com) I've come across many methods and I'm learning many things. But as I want to master this language, I'm taking some time to dive into some new things I learn every day. Today I want to go in depth on:

## How does `.chomp` method work?
First of all, put in mind that Ruby is an Object Oriented language and everything in Ruby is an object. So, when we call the `.chomp` method on a value/object it removes the line break.

Actually, what `.chomp` does, is removing the Enter character at the end of your string. When you type _d e v t o_, each character at a time and then press Enter `gets` takes all the letters and the Enter. Remember that Enter is just another character in Ruby.

For example:
```ruby
input = gets # get a string
Bem Vindo
=> "Bem Vindo\n" # when you hit the enter keyboard it adds a character
```
Now let us remove that enter character

```ruby 
puts input.chomp
```

or we can remove right away when typing it
```ruby
input = gets.chomp # gets require a string as input and chomp will delete the line break that comes with that string
```

`gets` is your User's input. Also, it's good to know that gets or puts, mean *get string* or *put string* for `puts`. That means these methods are dealing with strings only.

We can even use the `.chomp` method to remove a substring of a string in that way.

```ruby
str = "Hello"
str.chomp("lo")
```

### Resources:
[What is Ruby](https://whatis.techtarget.com/definition/Ruby)

[Help and documentation for the Ruby programming language.](http://ruby-doc.com/docs/ProgrammingRuby/)

[Everything is object in Ruby](https://medium.com/@pk60905/everything-is-object-in-ruby-559475ce71dd)

[Chomp method - Ruby Docs](https://ruby-doc.org/core-2.2.0/String.html#method-i-chomp)


Thanks.

