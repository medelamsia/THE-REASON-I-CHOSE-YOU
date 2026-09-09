# DIRECTOR SPEC

## Role
The episode files are written as a director's adaptation brief, not as a final storyboard and not as a simple summary.

The downstream workflow is:
Source chapter → episode brief → storyboard → image/video generation.

## Required information in every episode
Every episode preserves these layers:
1. Story Beat — what happens and why it matters.
2. Action / Blocking — what the characters physically do while the beat happens.
3. Dialogue Anchor — dialogue already supported by the source chapter.
4. Performance — how the character should emotionally play the beat.
5. Visual / Edit Direction — how the beat should be filmed/cut without changing the story.
6. Continuity — the emotional, spatial, relational, wardrobe, prop, and knowledge state carried into the next beat.
7. Carry-over — what state the next episode inherits.

## Part semantics
PART 1, PART 2, etc. are editorial production partitions.

They are NOT:
- six separate scenes;
- six separate stories;
- six mandatory 10-second shots;
- mandatory places to stop an actor's performance;
- reasons to reset blocking, wardrobe, emotion, lighting, or environment.

A part can be 2 seconds or 11 seconds when the overall episode remains ≤60 seconds. Multiple shots can occur inside a part.

The finished video should feel like one uninterrupted dramatic flow even when the production file is divided into parts.

## Runtime
HARD MAXIMUM PER EPISODE: 60 seconds.

Preferred range: approximately 45–60 seconds when the source needs it.

A shorter episode is valid. Never stretch a chapter with filler just to hit 60 seconds.

## Pacing
- Cut on action, reaction, interruption, reveal, or useful information.
- Use short shot lengths when tension is high.
- Do not insert walking, staring, establishing shots, or silence unless it advances the scene.
- Do not repeat information across parts.
- If a source action takes 3 seconds, let it take 3 seconds.
- Story momentum is more important than equalized part duration.

## Fidelity
The uploaded PDF is canon.

Allowed:
- compression;
- omission for runtime;
- combining source beats into one continuous visual sequence;
- changing camera angle;
- converting internal narration into visual acting where the meaning is preserved.

Not allowed:
- new plot events;
- new relationships;
- invented motivations that change causality;
- moving a reveal earlier solely because it is convenient;
- filler dialogue that changes character intent;
- changing the emotional consequence of a source event.

## Dialogue
Dialogue anchors in the episode files are source-supported references. During screenplay/storyboard expansion:
- prioritize the exact source line when it fits;
- shorten only when necessary for runtime while preserving meaning;
- do not invent dialogue that changes plot, motivation, or relationship state.

## Director decision hierarchy
When choices conflict, use this order:
1. Source canon
2. Continuity with previous/next episode
3. Causal story flow
4. Character performance
5. Pacing
6. Visual style

Visual spectacle must never override story causality.

## Episode titles
Titles are optional metadata/packaging. They are not part of the story structure.

The important continuity is:
EP(n) ends → EP(n+1) begins from that exact dramatic state.

## Custom GPT handoff
When a later GPT reads an episode file, it should treat it as the authoritative adaptation brief for that episode and use CANON.md plus neighboring episodes to resolve continuity.

Do not regenerate the plot from memory when an episode file already specifies it.
