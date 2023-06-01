# Basics of Algorithm<br/>
<br/>

### **Definition of Algorithm**
- An algorithm is a finite set of step by step, discrete, unambiguous instructions for solving a particular problem.
- Has input data, and is expected to produce output data.
- Each instruction can be carried out in a finite amount of time in a deterministic way.<br/>

In simple terms, an algorithm is a series of instructions to solve a problem.<br/><br/>

### **Properties of Algorithm**
- #### **Effectiveness**
    - It will be simple.
    - It can be carried out with pen and paper.
- #### **Definiteness**
    - It will be clear.
    - Its meaning will be unique.
- #### **Correctness**
    - It will give the right answer for all possible cases.
- #### **Finiteness**
    - It will stop at a reasonable time.
<br/><br/>

### **The steps required for algorithm design**
- Pseudo code
- Prove correctness
- Analyze the algorithm
    - Best case efficiency
    - Average case efficiency
    - Worst case efficiency
<br/><br/>

### **What is the need to study Algorithms?**
<p>A computer may be fast, but they are not infinitely fast. And memory may be inexpensive, but it is not free. So, computing time and memory space is a bounded resource. By learning algorithms,  we can use these resources intelligently. And algorithms that are efficient in terms of time or space will help us do this. So we need to study algorithms.</p><br/>


### **Best, Worst, and Average-Case Complexity**

-  The best-case complexity of the algorithm is the function defined by the minimum number of steps taken in any instance of size n.<br/>
-   The worst-case complexity of the algorithm is the function defined by the maximum number of steps taken in any instance of size n.<br/>
-   The average-case complexity of the algorithm, which is the function defined by the average number of steps taken over all instances of size n.<br/>

### **The efficiency of an algorithm**

The efficiency of an algorithm defines the number of computational resources used by an algorithm and the time taken by an algorithm to produce the desired result.
The efficiency of an algorithm depends upon 3 factors.
1. Space
2. Time 
3. Other factors like comparisons, amount of stack memory used, etc.<br/>

### **Time complexity**

<p>Time complexity is the computational complexity describing the amount of time required for the execution of an algorithm. Time complexity measures the time taken by every statement of the algorithm. It highly depends on the size of the processed data. It helps to define the effectiveness of an algorithm and to evaluate its performance.</p><br/>

### **Space complexity**

<p>When an algorithm is run on a computer, it uses a certain amount of memory space. This required amount of memory space is represented by space complexity.<br/></p>

### **Time Efficiency**
<p>Time efficiency is the amount of time required to execute an algorithm.<br/></p>

### **Space Efficiency**
<p>Space efficiency is the amount of memory required to execute an algorithm.<br/></p>

### **What is Order of Growth?**

<p>Order of growth is a set of functions whose asymptotic growth behavior is considered equivalent. For example, 2n, 100n, and n+1 belong to the same order of growth which is written O(n) in Big-Oh notation and is often called linear because every function in the set grows linearly with n.<br/></p>

### **<br/>Why do we use O-notation?**
<p>Big O Notation is one of computer science's most necessary mathematical notations to measure an algorithm's efficiency.<br/> 
Big O Notation tells us how well an algorithm will perform in a particular situation.
In other words, it gives an algorithm's upper-bound runtime or worst-case complexity.<br/>
For the sake of analysis, we ignore constants: O(C * f(n))  = O(g(n)) or O(5N) = O(N).<br/>
So, we use O-natation to describe the amount of time a given algorithm would take in the worst case, based on the input size n.<br/></p>




