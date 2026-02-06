🏆 Causal Conversational Analysis for Pravaah’26
🚀 Overview

This project presents a causal analysis and interactive reasoning system built over conversational transcripts for the Pravaah’26 IIT Bhubaneswar Data Science Hackathon.
Unlike traditional event detection systems, this solution focuses on explaining why outcome events occur, grounding each explanation in traceable conversational evidence, and enabling context-aware multi-turn analytical interaction.

A key innovation of this system is its ability to adapt causal reasoning strategies under anonymized conversational data, ensuring faithful, non-hallucinatory explanations even when lexical content is unavailable.


🎯 Problem Statement

Conversational systems generate large volumes of multi-turn dialogue data associated with outcome events such as delivery investigations or escalations. While identifying such events is straightforward, understanding which conversational behaviors causally contributed to these outcomes and enabling follow-up analytical reasoning remains a challenge.

This project addresses that challenge by:

Moving from event detection to causal explanation

Linking conversational behavior to outcomes using evidence-grounded reasoning

Supporting multi-turn, context-aware queries over conversational data


🧠 Core Innovation
Adaptive Causal Reasoning under Anonymized Data

The provided dataset contains redacted conversational utterances represented by placeholders. Rather than hallucinating text or forcing unreliable sentiment analysis, this system intelligently adapts by:

Detecting data anonymization

Switching from lexical analysis to structural conversational reasoning

Inferring causality from interaction patterns such as repetition and turn sequencing

This design ensures:

Perfect faithfulness

Zero hallucination

Robust causal explanations despite data constraints

This adaptive behavior is the system’s key innovation.


🧩 Approach & Methodology
🔹 Task 1: Causal Analysis with Evidence

Conversational transcripts are reconstructed using speaker roles and turn ordering

Structural conversational features are extracted:

Repetition patterns

Interaction sequencing

Causal evidence is explicitly linked using:

conversation_id

turn_id

Each explanation is traceable back to concrete evidence

This satisfies ID Recall and Faithfulness metrics



🔹 Task 2: Multi-Turn Context-Aware Reasoning

A Context Manager stores analytical state across user queries

Follow-up questions are interpreted based on prior responses

The same causal framework and evidence base is reused across turns

This ensures conversational coherence and consistent reasoning.


🧠 Concepts & Techniques Used
🔹 Machine Learning & Data Science

Causal reasoning (non-correlational)

Evidence-grounded explanation

Feature engineering

Structural pattern analysis

Data-aware model adaptation

🔹 NLP & Conversational Analysis

Multi-turn conversation reconstruction

Speaker role modeling

Interaction pattern analysis

Contextual query understanding

🔹 System Design

End-to-end ML pipeline

Context manager for state preservation

Faithfulness & hallucination control

Reproducible and modular codebase



