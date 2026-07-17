Repeated Replacement (Wine and Water) – Complete Understanding

Whenever I see a question where some quantity of liquid (wine, milk, acid, etc.) is removed from a full container and then the container is filled again with another liquid, I should never think that the same amount of the original liquid is removed every time. This is true only for the first operation. After the first refill, the container no longer contains pure wine; it contains a mixture of wine and water. Therefore, during the second, third, and later operations, I remove both wine and water together. Solving this by calculating the exact amount of wine after every operation becomes lengthy. Instead, I should think in terms of the "Survival Fraction". I should ask myself one simple question: "What fraction of the original wine survives after one operation?"

Suppose the capacity of the container is V litres and every time d litres are removed. Since d litres are removed from a total of V litres, the fraction removed is d/V. Therefore, the fraction of wine that survives after one operation is (1 − d/V). This is the only idea I need to remember. Every operation keeps only this surviving fraction of the wine. So if initially there are V litres of wine, after the first operation the wine becomes V × (1 − d/V). After the second operation, the same surviving fraction is applied again, giving V × (1 − d/V)². After the third operation it becomes V × (1 − d/V)³. Continuing this process, after n operations the remaining wine becomes:

Wine Left = V × (1 − d/V)^n

Notice that I do not need to memorize this formula. It comes naturally from the idea that after every operation, only the same surviving fraction of wine remains.

Now solve the question.

The capacity of the cask is unknown, so let it be V litres. Every time 8 litres are removed and the operation is repeated 4 times. Therefore,

Wine Left = V × (1 − 8/V)^4

The question also tells me that at the end the ratio of Wine : Water is 16 : 65. The total parts are 16 + 65 = 81. Therefore, the fraction of wine left is 16/81 of the total capacity.

So,

Wine Left = (16/81)V

Since both expressions represent the amount of wine left, I equate them.

V × (1 − 8/V)^4 = (16/81)V

Cancel V from both sides.

(1 − 8/V)^4 = 16/81

Now observe that

16 = 2^4
81 = 3^4

Therefore,

16/81 = (2/3)^4

Hence,

1 − 8/V = 2/3

So,

8/V = 1/3

Therefore,

V = 24 litres

Hence, the original capacity of the cask is 24 litres.

The most important thing to remember is not the formula but the idea behind it. Every replacement removes the same fraction of the original liquid, not the same amount. Therefore, after every operation only the surviving fraction remains. If I remember this one idea, I can derive the formula during the exam even if I forget it.

Memory Trick:

Instead of memorizing the formula, remember only this sentence:

"Every replacement keeps only a fixed fraction of the original liquid alive. Therefore, after every operation I simply multiply by the same surviving fraction again."

Whenever I see the pattern:

Remove → Refill → Repeat

I should immediately think:

Remaining Quantity = Initial Quantity × (Survival Fraction)^Number of Operations

where,

Survival Fraction = 1 − (Quantity Removed / Capacity)

This single concept is enough to solve almost every repeated replacement question asked in TCS NQT, Infosys, Accenture, Wipro, Capgemini, Cognizant and similar placement exams.
