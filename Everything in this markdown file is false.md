
# The Liar Paradox

### Background Information 

The liar paradox is probably the most infamous and well-known paradox in history. It dates back to at least Eubulides in ancient Greek times. However, a variation of the liar paradox appears in the Bible, in St. Paul's letter to Titus. In which he says in verses 12-13:

>  One of Crete’s own prophets has said it: “Cretans are always liars, evil brutes, lazy gluttons.”[c] 13 This saying is true. 

So the paradox is rather ancient, and it has pretty big implications, most notably for our theories of truth, logic, and semantics.

It is also deadly! So tread carefully! Philitas of Cos died due to the insomnia this philosophical problem caused for him! So you gotta watch out as we continue.

I will start with 1. Constructing the paradox, 2. air out some potential solutions others have come up with related to the paradox, as well as discussing the issues with these solutions. Lastly, I will try to add something to the discussion related to the liar paradox.

### What is the liar paradox?

The liar paradox goes something like this.

> L1: L1 is False

You may have heard this described to you before as,
> This sentence is false

This can run us into some issues in terms of generating the paradox. The reason is that it can be unclear what "This sentence" refers to. To avoid that, we name the sentence. We name things all the time. So there should be nothing wrong with naming the sentence "L1". Therefore, the sentence can refer to something (in this case, its own truth value) without any ambiguity.

The problem with L1 is as follows. Is L1 true? Well, if L1 is true. Then it must be false. Consider that if a sentence is to be true, then whatever it says of itself must be true, and if L1 says of itself that it is false, it must be false! Right? Well, let us consider whether L1 is false. If L1 is false, then it must be true? Right? Consider that if a sentence is false, and it also says of itself that it is false, it must be saying something true about itself, a truth about its falsity. Therefore, making the sentence L1 true? SO therefore, if L1 is true, then it is false.
On the other hand, if L1 is false, then it is true?? Wait a minute. How is this possible? Is this a paradox? 

Well, not yet; we have only constructed two statements about L1:

Well, not yet; all we have constructed are two statements about L1.

> a) If L1 is true, then it is false
> b) If L1 is false, then it is true

This can also be described as:

> a') If L1 is true, then it is not true
> b') If L1 is false, then it is not false

(The reason for this alternative description has to do with the principle called *consequentia mirabilis* or the principle of implied negation. If statement A is true, then it must imply its own negation, ~A (the ~ means "not"). If L1 is true, then it is false (therefore not true), and if it is false, it is true (therefore not false). So one can say a') If L1 is true, then it is not true, as well as b') If L1 is false, then it is not false)

This is not yet a paradox, as we need a principle that would show that a') and b') cannot coexist; if not, we can say that L1 is neither true nor false. Luckily, we have such a principle. We have this principle in logic called the principle of bivalence. The principle of bivalence states that **sentences must have one truth value, either True or False. ** 

The principle of bivalence gives us reason to think this is a paradox: L1 cannot be true, or it is not true. L1 cannot be false, or it will not be false; and if the principle of bivalence holds, it also cannot be neither true nor false, because all sentences need a truth value! 

Our first line of attack would be to show that the principle of bivalence does not apply to the sentence. If the principle of bivalence does not apply, then we would have grounds to declare the sentence neither true nor false. Therefore, in some sense, we escape the problem. We would still have to give an account of why such sentences can avoid truth values altogether, but at least this way we will get closer to resolving the issue of paradox.

### Is the principle of bivalence right?
As I have said, the principle of bivalence states that all sentences must have a truth value. However, this cannot possibly be the case. Take, for instance, questions. Questions do not have truth values. They ask something about the world that could be true or false. However, for someone to ask the question "Is it raining outside?" is not to say "It is true that it is raining outside" or "It is false that it is raining outside." It is simply to ask a question. So maybe we should amend the principle of bivalence to say 

> The principle of bivalence states that all declarative or propositional statements have to have a truth value. Either True or False.

So this removes questions. It also removes commands like "Go wash the dishes!" because those do not seem to have a truth value either. Either way, maybe we can pick apart this as well. Take the statement

> The Elephant is not about to charge.

Is this true or false? Well, it does not seem true, because there is no elephant? However, saying it is false is not accurate either. It is not false simply because there is no elephant at all that could charge in the first place. The sentence then seems semantically defective (our professor has said this sort of example is very controversial; some philosophers think sentences like this are actually just false).


To speak to this example more, it is not true because there is no elephant around us, and it is not false because saying it is false means saying there **is an elephant about to charge**, which is not true. There is no elephant around. So the sentence is semantically defective because the context is misplaced. People do not normally say something like this unless they have reason to believe there is an elephant in the first place. Hopefully this makes more sense now!

Hopefully you can see the sort of reasoning that would lead someone to say that it is neither true nor false. If statements like this, which are semantically defective, have no truth value. We should amend the principle of bivalence further to say 

> The principle of bivalence states that all declarative or propositional, ** non-semantically defective** statements have to have a truth value. Either True or False.

Therefore, we can say that L1 is neither true nor false. If we can show that it is a defective sentence in some way. This is the approach taken by Saul Kripke in his paper[ Outline of a Theory of Truth](https://philpapers.org/rec/KRIOOA) and Alfred Tarski's paper [The Semantic Conception of Truth: and the Foundations of Semantics](https://sites.ualberta.ca/~francisp/Phil426/TarskiTruth1944.pdf)
