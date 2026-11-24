# 33n.b: learnings

- 33n.vc is a Framer site; its search index JSON holds the text of every page and was the most complete source.
- Portfolio entries on 33n.vc are logos only. Names were taken from link targets; where no name was shown, the entry is marked unconfirmed rather than guessed.
- The home page says both "4 unicorns" and "three unicorns at their earliest rounds". Both are kept as published, with the inconsistency noted.
- A sandboxed srcdoc viewer breaks links: '#' links must scroll inside the frame, and outside links must be handed to the parent page, which opens them with noopener.
- axe-core needs bypassCSP to run on a page with a strict CSP.
- The SSH agent used for commit signing does not survive between turns: restart it and re-add the key each time, one command per step.
- A share card for a private preview should show only the holding page's own words (conductor.b's review).
