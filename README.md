# Let's test some Repls!

Below are some repls, some with multiple validations, some with only 1 validation. They should all work.

%%%

### Ruby Repl Multiple Validations (`assert_output` and `assert_length`)

Write a method that returns 'ruby'

~~~ruby

def puts_ruby
  # code your solution here
end

# do not remove the line below
puts_ruby

~~~solution

def puts_ruby
  puts "ruby"
end

puts_ruby

~~~validation 

assert_output(response, "ruby\n")
assert_length(response, 5)

~~~

%%%

Moving right along...

%%%

### Ruby Repl Multiple Validations (`assert_equal` and `assert_length`)

Write a method that returns 'ruby'

~~~ruby

def return_ruby
  # code your solution here
end

# do not remove the line below
return_ruby

~~~solution

def return_ruby
  "ruby"
end

return_ruby

~~~validation 
 
assert_equal(response, "ruby")
assert_length(response, 4)
 
~~~

%%%

Now one with no whitespace...

%%%

### Ruby Repl - One Validation (`assert_equal`)

Write a method that reverses a string, and call it, passing "12345" as an argument.

~~~ruby

# Code your solution here

~~~solution

def reverse(string)
  string.reverse
end

reverse("12345")

~~~validation

assert_equal(response, "54321")

~~~

%%%
