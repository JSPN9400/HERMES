# Why HERMES?

Problem:
Transformer self-attention compares many tokens, which becomes expensive for long contexts.

Hypothesis:
Instead of reasoning over all tokens immediately, first identify semantic concepts, route work to specialized experts, exchange only necessary information, verify globally, then generate the answer.

This is a research hypothesis, not a proven improvement.
