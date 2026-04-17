# Step by step on how I leetcode / approach problems

Tbh the way I do it is to just Leetcode and learn DSA along the way. Here's how I would go about it and I think you should too

1. Go on [Neetcode](https://neetcode.io)
2. Make an account
3. Go to the [blind 75 list](https://neetcode.io/practice/practice/blind75) (I know I said 150 before, but neetcode 75 is also a good starting point).

Here's how I would go about solving each leetcode problem _(let's take the very first problem in the 75 list, "Contains Duplicate" as an example). **Make sure to switch code to Python / Python3 since it's a lot easier for solving leetcode problems.**_

1.  Read the first paragraph / passage then skim through the rest. _(since "Contains Duplicate" doesn't have a lot of words to read, I would just read the whole thing slowly)_
2. Then look at examples to see how input and output works, in order to reinforce and understand what the problem is asking for

If I looked at the examples but still don't know what it's asking for then I would go back to the start and read everything over again, but slower this time

3. Now we can move onto writing in the editor. I usually prefer to pseudocode a solution first before writing any code. _(check image below)_
<img width="698" height="171" alt="image" src="https://github.com/user-attachments/assets/14a14656-1ebf-416e-81cb-46d40b0f1be1" />

4. Then run through the pseudocode with 2-3 examples to make sure it works. if any errors show up then fix up the pseudocode.
<details>
<summary><b>Cases</b></summary>
<br>
-----------------------------------

Think of 2 "happy cases" that would return you something, in this example: 
  
```
    input = [1,2,3,1] (this would return True)
    input = [4,3,6] (returns False).
```


And 1 "bad case" that would break the program. Example: 
```
  input = ["bob"]
  (TBH this would return False and would still work, but let's just pretend it returns NULL and breaks the program).
```
Then you would need to think of a way to prevent an input of "bob" from breaking the program. 
**Unless the problem says input will always be numbers, then don't worry about this specfic bad case.**

**-----------------------------------**
</details>
<br>

5. Finally, write the solution in python & submit
<img width="772" height="810" alt="image" src="https://github.com/user-attachments/assets/a30211de-0c33-4960-84e8-dc8c6b0b28f0" />



## Important Final Thoughts:
If at any point you're stuck for **3-5** minutes, from either reading the problem, writing the pseudocode, 
or writing actual the code. I would just open up the solution video and watch how they do it. 

When it comes to practicing Leetcode, the goal isn't to solve every problem without any help. 
Instead, it's to learn and understand which and what algorithm was used to solve the given problem and why. 
Therefore, the best way to learn _(leetcoding)_ is to watch/read from other people's solution.

I referenced this back in my other writing: [here](https://github.com/olafnub/andydoes-writing/blob/main/leetcode-with-habits.md)

### If there's anything to takeaway from this article, it's to:
1. Go through neetcode 75
2. Skim through readings, look at inputs & outputs, & reread slowly
3. **Pseudocode your solution! _& go through test cases_**
4. Write the code in python

### Resources
We all learn differently, but this is my experience on how I found myself enjoying leetcode a bit more. Here's other people's writing / experieince:
- https://dev.to/idsulik/empowering-newbies-building-confidence-through-600-leetcode-solutions-a-guide-for-beginners-3960
- https://medium.com/@austin-starks/heres-the-secret-to-getting-good-at-leetcode-that-nobody-ever-told-you-43a6d4852a44


