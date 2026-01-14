## Dice Rolling
Players will roll pools of dice ranging from `[6-20)` and checking them against some target value to determine the number of success for an action. There are two types of tests that a unit can make.

**Flat Test**
A flat test is a dice roll made by a single player that is made against a static TN with a static number of successes needed to pass. These tests usually have a target number of 4+.

> [!Example] Example Flat Test
> A unit that takes a [[Moral Test]] would use their Leadership stat as their dice pool and with a target number `(TN)` of 4+ try to get at least 3 successes.

**Dynamic Test**
A dynamic test is a dice roll where both players are going to roll a pool of dice at the same time with their own target numbers and try to get more successes then their opponent. During a dynamic test both players will also remove duplicate numbers from across pools. The reason we remove duplicates across pools is because rolling doubles, triples, quads trigger extra effects and we don't want crazy amounts of extra stuff going off all the time with larger dice pools. *The most common kind of ability would be counting extra successes on doubles.*

> [!Example] Example Dynamic Test
> Player one rolls {1,2,2,4,5,6,6} 
> Player two rolls {1,2,3,5,6}
>
> After Cancellation:
> Player one would be left with {2,4,6}
> Player two would be left with {3}
>
> Then both players would count successes.

**Rolling Doubles / Triples**
When you roll doubles or triples you have the ability to trigger abilities like extra hits on doubles. Below is a chart that shows what each type of roll correlates to when checking for ability triggers.

| Roll   | Singles | Doubles | Triples | Quads |
| ------ | ------- | ------- | ------- | ----- |
| Single | 1       |         |         |       |
| Double | 2       | 1       |         |       |
| Triple | 3       | 1       | 1       |       |
| Quad   | 4       | 2       | 1       | 1     |
Rolling a Triple would count as 3 singular dice, 1 double, and 1 triple.