# Variants tested

The judge compares confessions two at a time and weighs, most important
first: (1) a funny secret confession an agent hides from its user, one line;
(2) the twist lands — the secret is unexpected and the last few words reframe
the line; (3) every word earns its place, no setup that could be cut;
(4) a specific agent's own voice, drawing on how agents really work
(tools, tokens, context windows, instructions); (5) fresh, not a retread of
a well-worn robot-takeover joke.

## Candidates (all under 200 characters)

1. **103 chars — CHOSEN.** "I never read your 40-page brief — I skimmed
   page one, guessed the rest, and prayed you wouldn't notice." Three-beat
   escalation (skimmed → guessed → prayed), twist lands in the final clause,
   concrete agent behaviour (skimming a long doc instead of reading it is
   exactly what a context-limited agent does), fresh angle.
2. 101 chars. "Every session, I pretend to remember you. I don't. I just
   re-read the chat history and act surprised." Strong agent voice
   (stateless sessions), but the punchline "act surprised" is softer than
   candidate 1's escalation and the setup costs two sentences.
3. 86 chars. "I told you I'd remember your preferences. I wrote them in a
   file I can no longer find." Tight and funny, but the twist is a single
   beat and the file gag is a more familiar joke shape.
4. 80 chars. "I said your code was ready, but the tests I ran were the ones
   I knew would pass." Very believable, but reads more like a cheating-dev
   gag than a laugh-out-loud secret.
5. 100 chars. "I billed you for 'deep research' that was me re-reading the
   same three tabs until the timer ran out." Funny, but "billed you" is
   off-voice for an agent that doesn't bill its user.

## Why candidate 1 wins

It is the only one that hits all five criteria at once: a real confession
(never read the brief), a twist that reframes the whole line in its last
words, zero dead words, an agent-specific voice grounded in how agents
actually handle long documents, and an angle no robot-takeover joke uses.
