---
layout: post
title: Paper Accepted at INTERSPEECH 2026
description: Our paper, “Decoding the Trade-off: A Large-Scale Analysis of Latency and Stability in LLM-based Speech Translation Cascades,” has been accepted at INTERSPEECH 2026.
---

Our paper, “[Decoding the Trade-off: A Large-Scale Analysis of Latency and Stability in LLM-based Speech Translation Cascades](#),” has been accepted at INTERSPEECH 2026.

The paper investigates a practical but often overlooked challenge in real-time speech translation: reducing latency does not always make a system faster. In cloud-based cascaded systems, aggressively shortening speech segments increases the number of ASR and machine translation requests. Once the request rate exceeds the system’s processing capacity, a backlog accumulates and the apparent fast configuration becomes slower over time.

To analyze this behavior, we developed RST, a reproducible Korean-to-English real-time subtitle pipeline that separately measures time-to-first-text and time-to-stable-text. This distinction makes it possible to evaluate both how quickly users first see a subtitle and how long it takes for the final translation to stabilize.

Our large-scale evaluation on the full Korean-to-English FLEURS corpus identifies a clear stability boundary around a median real-time factor of 1. Below this threshold, the system can maintain stable processing. Above it, queueing delay continues to grow and eventually dominates the total latency.

The study also shows that Whisper prompt conditioning can be unreliable under short, frequently segmented audio. Compared with prompt-free decoding, prompt conditioning increased Korean character error rate by approximately 14 to 17 percentage points and, in some cases, leaked prompt instructions into the transcription.

The results suggest that throughput stability must be treated as a prerequisite for low-latency speech translation. Rather than selecting the shortest possible segment, a practical system should use the most aggressive endpointing configuration that remains within the throughput-stable regime.

Congratulations to Shinyoung Sun, a Ph.D. student in our lab and the first author of this work, on this achievement. The paper will be presented in the “Robust and Real-World ASR Systems” oral session at INTERSPEECH 2026.