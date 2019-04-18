---
layout: post
title:      "Removing Unwanted Junk from Arrays "
date:       2019-04-18 02:09:06 +0000
permalink:  removing_unwanted_junk_from_arrays
---


This blog will be the first in a series I’ve decided to write about useful ruby array methods. Several times throughout the curriculum, I have written my own method for manipulating or interacting with arrays, only to show my code to someone else and have them say, “Why didn’t you just use (insert built-in Ruby array method here)?” I always feel a mix of embarrassment at my naivete and excitement that there is an easier way to do things. Wow, Ruby is such a cool language! But clearly I need to brush up on my Ruby array methods and should be spending more time checking out the Ruby Documentation. 

Today I’m going to discuss two array methods that deal with removing unwanted junk from arrays—*uniq* and *compact*. The purpose of *uniq* (which I’m assuming comes from the word “unique”), is to return a new array with all duplicate values removed. The method *uniq!* Is similar, but instead of returning a new array and leaving the old one unchanged, it modifies and returns the original array. It will return “nil” if there were no duplicates and the array is not changed. I remember using this method during one of the labs that worked with artists and songs. I wanted to return a list of all the artists with each artist listed only once, and it did the trick. 

The second array method is *compact*. This method returns a new array with all “nil” elements removed. Like *uniq/uniq!*, there is a similar method available for modifying the array in place instead of returning a new one—*compact!* And like *uniq!*, *compact!* will return “nil” if no changes were made (in this case, if no “nil” elements were found). I remember using this method during one lab that required me to import data. The data included several “nil” elements sprinkled throughout, which were messing up my code. This elegant method solved the problem.

Now I know what you must be thinking at this point. What should we do if we want to remove all duplicate AND “nil” elements in an array? Because Ruby is so cool, it allows us to chain methods together. We could simply use `example_array.uniq.compact` 
*or *
`example_array.compact.uniq` 
to do both!

