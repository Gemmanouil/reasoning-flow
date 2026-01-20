

Objective: Guide the model to solve a problem with explicit reasoning.

Write a logic puzzle (e.g., "Alice is older than Bob, Bob is older than Carol. Who is the youngest?").

Prompt the model: "Explain your reasoning before giving the final answer."

Verify that the model provides step-by-step reasoning followed by the correct answer.

here is a puzzle. There are 2 doors, one goes to heaven and one to hell, and 2 guards besides them, one guard tells only truths and one only lies, how can u define which is which with just one question. Explain your reasoning before giving the final answer.

Ah, the classic “two doors, two guards” puzzle! Let’s reason carefully step by step.

Step 1: Understand the situation

There are 2 doors: one to heaven, one to hell.

There are 2 guards: one always tells the truth, the other always lies.

You don’t know which guard is which, and you can ask only one question to one guard.

Goal: figure out which door goes to heaven (or equivalently, which guard is the truth-teller).

Step 2: Why asking “Which door is heaven?” directly doesn’t work

If you ask the truth-teller, he points to heaven → correct.

If you ask the liar, he points to hell → wrong.

✅ Problem: you don’t know if the guard is lying or telling the truth, so a direct question won’t guarantee a correct answer.

Step 3: Use a self-referential trick

We can ask a question that forces both guards to give the same answer, no matter if they lie or tell the truth.

The trick is: ask something like:

“If I asked the other guard which door leads to heaven, what would he say?”

Reasoning:

If you ask the truth-teller:

He will tell you what the other (lying) guard would say.

The liar would point to hell → truth-teller truthfully reports “hell.”

If you ask the liar:

He lies about what the other (truth-telling) guard would say.

The truth-teller would point to heaven → liar lies and says “hell.”

✅ Result: both guards will indicate the same door, which is the wrong door.

So you then choose the opposite door to go to heaven.

Step 4: Final Answer

Question to ask (to either guard):

“If I asked the other guard which door leads to heaven, what would he say?”

Then choose the opposite door from the answer.

This works because the question catches the liar in a double reversal, so no matter who you ask, the logic guarantees you know which door is safe.\

It followed the steps correctly with a solid logic.
