# Reverse Each Word

## Objectives

1. Practice using enumerators like the `.collect` method.
2. Practice converting between strings and arrays.

## Instructions

Fork and clone this repository. Run the test suite with the `learn` command. 

Write a method called `reverse_each_word` that takes in a string argument of a sentence and returns that same sentence with each word reversed in place. 

For example:

```ruby
reverse_each_word("Hello there, and how are you?")
  #=> "olleH ,ereht dna woh era ?uoy"
```

**Hint:** *You can't use an enumerator on a string, so how can we turn our string into an array?*

**Hint:** *How can we reverse each word and return those altered words? Remember that* `.each` *returns the original array but other enumerators don't.*