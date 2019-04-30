# Enumerator Quiz

## Objectives

Become familiar with using common iterators introduced in the previous lesson.

???

# Code Challenge

?: Using `.each`

Let's try out the enumerator methods we just learned. Refer back to the
previous lessons to help you pass this challenge. Below, we have a variable,
`lunch_menu`, set equal to an `Array` of lunch menu items.

Since you're super-hungry and super-excited about lunch, use the `.map` method
to enumerate over the `Array` and append an `"!"` ("exclamation mark") to each
menu item.


``` ruby
lunch_menu = ["pizza", "sandwich", "sushi", "soup", "salad"]
```

Which piece of code will achieve the desired result?

( )
``` ruby
lunch_menu.reduce{|memo, item| memo << item }
```
(x)
``` ruby
lunch_menu.map{|item| "#{item}!" }
```
( )
``` ruby
lunch_menu.reduce{|item, memo| memo += item }
```
(x)
``` ruby
lunch_menu.map{|item| item + "!" }
```

?: Using `.collect`

Below we have a variable, `nums`, set equal to an `Array` of numbers. Enumerate
over the `Array` and return a new `Array` of the squares of those numbers.


``` ruby
nums = [1, 2, 3, 4]
```

Which piece of code will achieve the desired result?


(x)
``` ruby
nums.collect { |n| n * n }
```
( )
``` ruby
nums.collect do |n|
  n + n
end
```
( )
``` ruby
nums.collect { |n| nn }
```
( )
``` ruby
nums.collect do |n|
  n
end
```

?: Using `.select`

Below we have a variable, `odds_and_evens`, set equal to an `Array` of numbers.
Use the `.select` enumerator to iterate over the `Array` and return any even
numbers. This requires checking if a number is even. If you're unsure how to do
that, reference the Ruby Documentation for `Integer` or try a Google search!

``` ruby
odds_and_evens = [1, 3, 2, 18, 5, 10, 24]
```

Which piece of code will achieve the desired result?

( )
``` ruby
odds_and_evens.select do |n|
  n / 2
end
```
(x)
``` ruby
odds_and_evens.select do |n|
  n % 2 == 0
end
```
(x)
``` ruby
odds_and_evens.select do |n|
  n.even?
end
```
( )
``` ruby
odds_and_evens.select do |n|
  n + 2
end
```

?: Using `.find`

Below we once again have a variable, `odds_and_evens`, set equal to an `Array` of
numbers. This time, use the `.find` method to iterate over the `Array` and return
only the *first* `Array` element that is *odd*.


``` ruby
odds_and_evens = [2, 3, 2, 18, 5, 10, 24]
```

Which piece of code will achieve the desired result?

( )
``` ruby
odds_and_evens.find do |num|
  num.even?
end
```
( )
``` ruby
odds_and_evens.find do |num|
  num / 2
end
```
( )
``` ruby
odds_and_evens.find do |num|
  num
end
```
(x)
``` ruby
odds_and_evens.find do |num|
  num.odd?
end
```

?: Using `include?`

Below we have a variable, `famous_cats`, set equal to an `Array` of famous
cats. Use the `.include?` method to check and see if the `Array` includes the
string `"Maru"`.


``` ruby
famous_cats = ["Maru", "Lil Bub", "Grumpy Cat"]
```

Which piece of code will achieve the desired result?


(x)
``` ruby
famous_cats.include?("Maru")
```
( )
``` ruby
famous_cats.include?
```
( )
``` ruby
famous_cats.include?(true)
```


???

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/enumerator-coding-challenge' title='Enumerator Coding Challenge'>Enumerator Coding Challenge</a> on Learn.co and start learning to code for free.</p>
