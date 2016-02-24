---
title: Hashes
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a Hash?

A hash is an unordered collection of data that is organized into key/value pairs.

# What are some examples of information that would be Hashes as opposed to some other data type?

A hash could be used to store a set of user names or email addresses, data that is unique.

# How are Hashes and Arrays similar? How are they different?

Hashes are similar to arrays in that they have slots that point to objects. In an array, the slots are numbered and in a row. In a hash, the slots are not numbered and you can use any object to refer to a slot, beyond numbers.

# How do you retrieve a particular value from a Hash?

This can be achieved by using hash[key]

# How do you add information to a Hash?

To add information to a hash use hash["new key] = value

# How would you perform an operation on every element inside a Hash?

Use the 'each' method.
    ex. hash.each {|key, value| puts "#{key} is #{value}" }

# How would you change the value of a particular element in a Hash?

To change the value you would specify the key and enter a new value.
    ex. hash["key] = newvalue

# How do you delete an element from a Hash?

Use the 'delete' method.
    ex. hash.delete("key") 

# What happens if you try to retrieve an element from a Hash that does not exist in the Hash?

If you try to retrieve an element that does not exist 'nil' will be returned.

# How do you determine how many elements are in a Hash?

Use the 'size' method.
    ex. hash.size