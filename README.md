
    Add to README.md
    Find All Duplicates

    Write a function (or static method in the case of Java) that accepts a list of integers and returns a list of only those integers that appear more than once.

There are two main ways to find duplicates in a list of integers. The first is the nested loop method, where each number is compared to every other number. If a match is found and hasn’t been recorded yet, it’s added to the list of duplicates. This method is easy to understand but can be slow for big lists because it checks many pairs of numbers, making it take longer as the list gets larger.

The second method uses a dictionary or set. As the program goes through the list, it keeps track of numbers it has already seen. If a number appears again, it’s marked as a duplicate. This method is much faster because it only looks at each number once and uses quick lookups. It does use a little extra memory, but it works much better for large lists.

In short, the nested loop is simple but slow for large lists, while the dictionary/set method is faster and better for handling more data.