```
# Queue
- write runnable code
- add code type after each code block





# Terms
- We encourage to dive in direct  code examples with explanations, we do Not encourage reading the doc completely without running an actual simple code.
- Learning by doing
- Fast way to improve level is going to attend partcipating a competition 
- The doc is written  over carefully for beginners. if it can not meet your spicy taste, please go directly to torch official doc.


# Prerequisite
- Python fammiliar



```





# torch
Torch is an elegant hammer to do the ml stuff. And this .md aims to record some comprehensions as myself.


**toc**
- tentsor
- a bird view of crashing a learning task
- a runnable code
- dataset manipulate


## tensor
Tensor is just a cube with multi dimensions. A scalar, vector, matrix is the subset of tensor. It can be seemed as entity. And like cube, we can roll it, swap it, crash it, and these called manipulation. There R so many manipulation that torch provides.
``` python
# list to tensor

# numpy to tensor

# tensor to list

# tensor to numpy

```



## A bird view of crashing a learning task
There R so many words, or professional words in ML field. And when dive in here, lots of people just scared, they R scared and want to escape. But, it's only a paper tiger. With some comprehensions, you can dive in more comfortable, and adapt to soon. Just follow the below steps.

First, we need to define something that is very basic mechanism in ML. No matter if your R a programmer or not, we all know that a Program is designed to make some calculation from input and produce result. Just like this:

Input -> Calc -> Output

For expample, check this code: 
```
def sum(a,b):
    return a+b

c=sum(1,2)  
```
Here `1` and `2` are  **Input**, `sum()` is **Calc**, `c` is **output**

Machine Learning is a program also, but it do a little different. It has two route, like below:

Knowned_things -> find_pattern -> Model  
Unknowned_things -> Model -> Known_now


These mechanism is vital, it exists in the whole lifetime of ML. So Try to familiar it. If you feel confusing, do not worry. just keep an initial impression to it. To people that first view this, it seems like robotic. But this is what ML do, lets check a example:

```
knowned_thing = {1:"odd",2:"even",3:"odd",4:"even"} 
unknown_thing = {5:""}

def get_some_pattern(a):
    return 'some code to find some pattern'

model=get_some_pattern(a)
known_now =model( unknown_thing ) 
```

The code can not run as it's just a preview mask many details but it do show the core steps in ML tasks.  We will fill details and runnable code soon.











 
