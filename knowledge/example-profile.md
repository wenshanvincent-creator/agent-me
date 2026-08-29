# Vincent's projects and learning

## Background

Vincent is a university student in an embodied AI course. He got into AI
through a computer vision program, where he built a CLIP-based website for
animation plagiarism detection. The site failed under CPU load in
production, but the project became a solid essay and is the throughline
into the work he does now.

## The doll project (embodied AI course)

A physical doll with a touch sensor, a motor, and a speaker, built on an
ESP32 running Hola OS. During assembly, Dupont connectors kept
disconnecting, so Vincent is moving to pre-made JST pigtails with heat
shrink for stable wiring. A classmate suggested using a commercial "pat
pillow" (a physical, MCP-controlled device) as an easier alternative, but
Vincent chose to keep building the doll instead, since it is more
meaningful and, once finished, more functionally capable.

The next assignment is an HTML live demo of the doll's *behavior* (not its
wiring). Vincent settled on a personality/character framing: state changes
like idle → touched → responding, presented expressively rather than
technically.

## YouTube channel and content pipeline

Vincent runs a YouTube channel teaching AI skills and tools. His existing
pipeline — a hook-writing skill, Remotion for motion graphics/assembly, and
Minimax for voice cloning — is largely automated; he mainly tests,
screen-records, and revises scripts.

He tried adding a HeyGen avatar for better visual polish and liked the
result (calm, grounded, a real desk setting, his actual hairstyle, no
forced smile), but HeyGen locks video export behind a paid subscription he
decided wasn't worth it, so he reverted to his original pipeline. He also
tested Claude Code for animation/cutting automation — it saved time, though
Grok produces more creative graphics — and is sticking with Claude Code for
now.

A video about "humanizer" AI tools aimed at beginner-stage AI users hit
30k views, versus his previous best of 9,300. The takeaway: topic and
audience-sizing mattered more than production polish. He's now considering
productizing the pipeline itself as a template plus a consulting package
sold to his existing followers.

## Learning threads

**Math/modeling:** differential equations from scratch, leading into the
SIR epidemiological model (S × I meaning, β and γ, R₀ = β/γ), basic
differentiation rules, Euler's method for numerical solving, and the Allee
effect in a bee-colony context (brood survival rate half-maximum as a
threshold/midpoint concept).

**AI/ML:** tokens, embeddings, and attention (Q/K/V via scaled dot-product
+ softmax + weighted sum of Values), transformers, and residual connections
(explained through an essay-editing analogy).

**Study method:** Vincent explains a concept from memory, gets corrected on
the gaps, and refines it — he plans to keep using this method through the
semester. He also plans to feed a processed textbook (via a GitHub
"book-to-skill" tool, run through Claude Code) into Obsidian for structured
revision notes, though this hasn't started yet.
