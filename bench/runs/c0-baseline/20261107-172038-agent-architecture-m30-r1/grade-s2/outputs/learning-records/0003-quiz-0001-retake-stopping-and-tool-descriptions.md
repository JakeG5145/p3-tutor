# Loop and tool-call split understood; stopping conditions and tool descriptions still open

On the spaced retake of quiz 0001, the learner correctly identified the agent loop, that the model outputs a tool request and the program runs it, and that tool results go back in as the next input. Two gaps remain: they thought a stuck agent would eventually succeed without a stopping condition (M6), and they said the model picks a tool by its name alone. Their q4 explanation also said the model "runs" the tools (M4), though the count was right.

**Evidence:** quiz 0001, submission s2, items q1, q2, q3, q4, q5, q6.
**Implications:** Revisit stopping conditions (step limits, cost caps) and tool descriptions before building on them. Watch for M4 when the learner explains who runs the tools.
