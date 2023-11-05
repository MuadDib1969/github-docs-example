# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in mrkdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use 3 backticks (`)
- Not to be confused with the quotation (')
```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end
puts "Enter a number:"
number = gets.chomp.to_i
result = factorial(number)
puts "The factorial of #{number} is #{result}"
```
