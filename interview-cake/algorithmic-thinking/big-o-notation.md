#Big O Notation

##The idea behind big O notation

**Big O notation is the language we use for talking about how long an algorithm takes to run.** It's how we compare the effciency of different approaches to a problem.

Big O notation expresses the runtime in terms of *horunning. Sw quickly it grows relative to the input, as the input gets arbitrarily large.*

**The breakdown**

1. **How quickly the runtime grows** - It's hard to pin down the *exact runtime* of an algorithm. There's a lot of factors to take into consideration such as the processor speed and whatelse the computer is running so instead we talk about *how quickly the runtime grows*.

2. **Relative to the input** - If we were measuring our runtime directly, we could express our speed in seconds. Since we're measuring *how quickly our runtime grows*, we need to express our speed in terms of...something else. With Big O notation, we use the size of the input, which we call "*n*." So we can say things like the runtime grows "on the order of the size of the input" (O(*n*)) or "on the order of the square of the size of the input" (*O*(*n^2*)).

3. **As the input gets arbitrarily large** - Our algorithm may have steps that seem expensive when nnn is small but are eclipsed eventually by other steps as *n* gets huge. For big O analysis, we care most about the stuff that grows fastest as the input grows, because everything else is quickly eclipsed as *n* gets very large. (If you know what an asymptote is, you might see why "big O analysis" is sometimes called "asymptotic analysis.")


-* Don't know what "Asymptote" is so this part is to understand it so I can see why "big O analysis" is sometimes called "asymptotic analysis"

**Ah-symp-totes**

From [Math Is Fun](https://www.mathsisfun.com/algebra/asymptote.html)
> 	An **asymptote** is a LINE that a curve approaches, as it heads towards infinity. The curve can approach from any side (such as from above or below for a horizontal asymptote), or may actually cross over (possibly many times), and even more away and back again. The important point is that the **distance** between the curve and asymptote **tends to zero** as they head to infinity (or -infinity)

So basically 