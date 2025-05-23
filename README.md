# CS221-Foundations-solved

Download Here: [CS221 Foundations solved](https://jarviscodinghub.com/assignment/foundations-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem 1: Optimization and probability
In this class, we will cast a lot of AI problems as optimization problems, that is, finding the best solution in a rigorous mathematical sense. At the same time, we must be adroit at coping with uncertainty in the world, and for that, we appeal to tools from probability.

[2 points] Let [Math Processing Error] be real numbers representing positions on a number line. Let [Math Processing Error] be positive real numbers representing the importance of each of these positions. Consider the quadratic function: [Math Processing Error]. What value of [Math Processing Error] minimizes [Math Processing Error]? You can think about this problem as trying to find the point [Math Processing Error] that’s not too far away from the [Math Processing Error]’s. Over time, hopefully you’ll appreciate how nice quadratic functions are to minimize. What problematic issues could arise if some of the [Math Processing Error]’s are negative?
[3 points] In this class, there will be a lot of sums and maxes. Let’s see what happens if we switch the order. Let [Math Processing Error] and [Math Processing Error], where [Math Processing Error] is a real vector. Does [Math Processing Error], [Math Processing Error], or [Math Processing Error] hold for all [Math Processing Error]? Prove it.
Hint: You may find it helpful to refactor the expressions so that they are maximizing the same quantity over different sized sets.
[3 points] Suppose you repeatedly roll a fair six-sided die until you roll a [Math Processing Error] (and then you stop). Every time you roll a [Math Processing Error], you lose [Math Processing Error] points, and every time you roll a 6, you win [Math Processing Error] points. You do not win or lose any points if you roll a 3, 4, or a 5. What is the expected number of points (as a function of [Math Processing Error] and [Math Processing Error]) you will have when you stop? Hint: it is recommended to think of defining a recurrence.
[3 points] Suppose the probability of a coin turning up heads is [Math Processing Error], and that we flip it 7 times and get [Math Processing Error]. We know the probability (likelihood) of obtaining this sequence is [Math Processing Error]. Now let’s go back and ask the question: what value of [Math Processing Error] maximizes [Math Processing Error]? What is an intuitive interpretation of this value of [Math Processing Error]?
Hint: Consider taking the derivative of [Math Processing Error]. You can also directly take the derivative of [Math Processing Error], but it is cleaner and more natural to differentiate [Math Processing Error]. You can verify for yourself that the value of [Math Processing Error] which maximizes [Math Processing Error] must also maximize [Math Processing Error] (you are not required to prove this in your solution).
[3 points] Let’s practice taking gradients, which is a key operation for being able to optimize continuous functions. For [Math Processing Error] (represented as a column vector) and constants [Math Processing Error] (also represented as column vectors) and [Math Processing Error], define the scalar-valued function [Math Processing Error] where the vector is [Math Processing Error] and [Math Processing Error] is known as the [Math Processing Error] norm. Compute the gradient [Math Processing Error].
Recall: the gradient is a [Math Processing Error]-dimensional vector of the partial derivatives with respect to each [Math Processing Error]: [Math Processing Error] If you’re not comfortable with vector calculus, first warm up by working out this problem using scalars in place of vectors and derivatives in place of gradients. Not everything for scalars goes through for vectors, but the two should at least be consistent with each other (when [Math Processing Error]). Do not write out summation over dimensions, because that gets tedious.
Problem 2: Complexity
When designing algorithms, it’s useful to be able to do quick back of the envelope calculations to see how much time or space an algorithm needs. Hopefully, you’ll start to get more intuition for this by being exposed to different types of problems.

[2 points] Suppose we have an image of a human face consisting of [Math Processing Error] pixels. In our simplified setting, a face consists of two eyes, two ears, one nose, and one mouth, each represented as an arbitrary axis-aligned rectangle (i.e. the axes of the rectangle are aligned with the axes of the image). As we’d like to handle Picasso portraits too, there are no constraints on the location or size of the rectangles. How many possible faces (choice of its component rectangles) are there? In general, we only care about asymptotic complexity, so give your answer in the form of [Math Processing Error] or [Math Processing Error] for some integer [Math Processing Error].
[3 points] Suppose we have an [Math Processing Error] grid. We start in the upper-left corner (position [Math Processing Error]), and we would like to reach the lower-right corner (position [Math Processing Error]) by taking single steps down and right. Define a function [Math Processing Error] to be the cost of touching position [Math Processing Error], and assume it takes constant time to compute. Note that [Math Processing Error] can be negative. Give an algorithm for computing the minimum cost in the most efficient way. What is the runtime (just give the big-O)?
[3 points] Suppose we have a staircase with [Math Processing Error] steps (we start on the ground, so we need [Math Processing Error] total steps to reach the top). We can take as many steps forward at a time, but we will never step backwards. How many ways are there to reach the top? Give your answer as a function of [Math Processing Error]. For example, if [Math Processing Error], then the answer is [Math Processing Error]. The four options are the following: (1) take one step, take one step, take one step (2) take two steps, take one step (3) take one step, take two steps (4) take three steps.
[3 points] Consider the scalar-valued function [Math Processing Error] from Problem 1e. Devise a strategy that first does preprocessing in [Math Processing Error] time, and then for any given vector [Math Processing Error], takes [Math Processing Error] time instead to compute [Math Processing Error].
Hint: Refactor the algebraic expression; this is a classic trick used in machine learning. Again, you may find it helpful to work out the scalar case first.
Problem 3: Programming
In this problem, you will implement a bunch of short functions. The main purpose of this exercise is to familiarize yourself with Python, but as a bonus, the functions that you will implement will come in handy in subsequent homeworks.

If you’re new to Python, the following provide pointers to various tutorials and examples for the language:

Python for Programmers
Example programs of increasing complexity
[3 points] Implement findAlphabeticallyLastWord in submission.py.
[3 points] Implement euclideanDistance in submission.py.
[4 points] Implement mutateSentences in submission.py.
[3 points] Implement sparseVectorDotProduct in submission.py.
[3 points] Implement incrementSparseVector in submission.py.
[3 points] Implement findSingletonWords in submission.py.
[6 points] Implement computeLongestPalindromeLength in submission.py.
