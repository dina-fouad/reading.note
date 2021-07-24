## Pain vs. Suffering

In  this course,we will learn far more than most people learn in 2 years of study in a University setting about software development, web app development. that is mean that price is pain, the pain of growth.

Do not confuse this with suffering.

Suffering is pain without purpose. Pain with no higher goal. Pain with no dreams, no ambition, no aspiration.

## Beginners Guide to Big O
Big O notation is used in Computer Science to describe the performance or complexity of an algorithm.

![](https://miro.medium.com/max/742/1*WBYUz6Lh2Z21DQnEk-MWFQ.png)

some common orders of growth along with descriptions and examples:

- **O(1)** describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

```
def func():     # The function definition is not considered as a step
    a = 10      # A variable is considered as a step
    b = 20      # A variable is considered as a step
    s = a + b   # A variable is considered as a step
    
    return s    # Return value is considered a step
```
*Execution Steps = 1 + 1 + 1 + 1 = 4 , Each step is iterated and executed only one time*

*Big O of any constant ==> O(1)*



- **O(N)** describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set. 

```
def func(n):
    
    s = 0
    

    for i in range(1, int((n + 1) / 2)):
        s += i
  
    return s
```

*Execution Steps = 1 + (n/2) + 1*

*Execution Steps = 2 + (n/2)*

*Big O of 2 + (n/2) ==> O(n)*


- **O(N²)** represents an algorithm whose performance is directly proportional to the square of the size of the input data set. 

```
bool ContainsDuplicates(IList<string> elements)
{
    for (var outer = 0; outer < elements.Count; outer++) 
    {
        for (var inner = 0; inner < elements.Count; inner++) 
        { 
            // Don't compare with self 
            if (outer == inner) continue;             
            
            if (elements[outer] == elements[inner]) return true; 
        }
    }    
    return false;
}
```

- **O(2^N)** denotes an algorithm whose growth doubles with each addition to the input data set. 

```
int Fibonacci(int number)
{
    if (number <= 1) return number;
       
    return Fibonacci(number - 2) + Fibonacci(number - 1); 
}
```

## Logarithms
Logarithms are slightly trickier to explain so I’ll use a common example:

Binary search is a technique used to search sorted data sets. It works by selecting the middle element of the data set, essentially the median, and compares it against a target value.

Facts and Myths about Python names and values

• Names and Values in Python 
• Python is a very approachable language.
 • Underlaying mehanisms are often qyite simple but their combined effects might not be what you expect.
  • Local names in the function are drawn in new frame .
