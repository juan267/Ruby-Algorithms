[Week 4 Home](../../)

# U2.W4: Calculate the Mode

## Learning Competencies
- Break a large problem down into smaller steps
- Implement a method based on pseudocode
- Iterate through data structures and manipulate the content
- Determine which data structure (arrays or hashes) to use based on challenge requirements
- Use strings, integers, arrays, and/or hashes


## Summary:

Write a method `mode` which takes an `Array` of numbers or strings as its input and returns an `Array` of the most frequent values.

If there's only one most-frequent value, it returns a single-element `Array`.

For example,

```ruby
mode([1,2,3,3])         # => [3]
mode([4.5, 0, 0])       # => [0]
mode([1.5, -1, 1, 1.5]) # => [1.5]
mode([1,1,2,2])         # => [1,2]
mode([1,2,3])           # => [1,2,3], because all occur with equal frequency
mode(["who", "what", "where", "who"]) # => "who"
```
HINT: You'll want to look at [`Hash`](http://ruby-doc.org/core-2.0.0/Hash.html)es for this challenge.
