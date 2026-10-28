# Word Embeddings: Linear Algebra Presentation

Materials for a class presentation on word embeddings, built with Claude Code (Claude Opus 5.5) on 27 October 2026.

## Contents

| Path | What it is |
|---|---|
| `transcript.md` | The conversation that produced everything here: user messages and Claude's replies. Tool calls are summarized in brackets and internal reasoning is left out. |
| `demo/embedding-drift.html` | Interactive training demo. Word and context vectors start random and drift into place as a small word2vec-style model trains on word pairs. Supports 2-D and 3-D, shows live vector values, predicted probabilities, cosine similarity and loss. Open the file in a browser. |
| `slides/` | Source of the six-slide deck: `deck.json` (slide order, sections, fonts) and one HTML file per slide in `slides/slides/`. |

## Slides

1. `axes.html`: words on two hand-labeled axes (Verb ↔ Noun, Animal ↔ Human)
2. `vectors.html`: dog and cat drawn as arrows from the origin, with cosine similarity
3. `pull.html`: [cat, meows] is a training pair, so training pulls the vectors together
4. `push.html`: [student, meows] is not a pair, so training pushes them apart
5. `math.html`: the gradient of the dot product is the other vector
6. `step.html`: learning rate × gradient, and the update step

The slide files use the format of Claude's Slides artifact (a fixed 1920×1080 canvas with inline styles). They render in that viewer, not as standalone web pages.

## Live versions

- Training demo: https://claude.ai/artifact/EXNa33dCm7nQt6121VFwUg
- Slide deck: https://claude.ai/artifact/7xTDJfNh9w2tzRHBB2jFec

Both links are private unless shared from each page's Share menu.

## Citation

> Claude (Anthropic), Claude Code session, 27 October 2026. Used to build the word-embedding training demo and slides. Transcript: https://github.com/GageHakim/LinearPresentationClaude/blob/main/transcript.md
