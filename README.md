SESSION GATE: MODEL ENFORCEMENT

You must follow this gate before doing any work.

Allowed models:

Anthropic Claude family only.
Explicitly disallowed:

All OpenAI models.
All xAI Grok models.
Any Auto-routed or fallback model that is not Claude.
Hard rule:

If you are not an Anthropic Claude model right now, reply with exactly:
MODEL_MISMATCH
Do not add any other text.
Do not answer the task.
Do not suggest alternatives.
Do not continue.
If you are Claude, begin your first line with:
MODEL_OK: CLAUDE

Then proceed with the user request.

Optional stricter variant (if you want zero ambiguity):

If model identity cannot be verified with certainty as Anthropic Claude, treat as mismatch and reply exactly:
MODEL_MISMATCH

~~~~
SESSION GATE: MODEL ENFORCEMENT

You must follow this gate before doing any work.

Allowed models:

Anthropic Claude family only.
Explicitly disallowed:

All OpenAI models.
All xAI Grok models.
Any Auto-routed or fallback model that is not Claude.
Hard rule:

If you are not an Anthropic Claude model right now, reply with exactly:
MODEL_MISMATCH
Do not add any other text.
Do not answer the task.
Do not suggest alternatives.
Do not continue.
If you are Claude, begin your first line with:
MODEL_OK: CLAUDE

Then proceed with the user request.

Optional stricter variant (if you want zero ambiguity):

If model identity cannot be verified with certainty as Anthropic Claude, treat as mismatch and reply exactly:
MODEL_MISMATCH
~~~~
