# Scenario 7 Task Decomposition

## Title 
Knowledge-aware Museum Guide for Virtual Heritage Exhibitions.

## Description 
An agent (Actor) with Q\&A (Capability) offers personalized guidance to visitors of  a virtual museum (Scenario)  based on their interests (EndGoal). Virtual reality  (InteractionTask) is used to predict multi-modal user inputs and reason  (both ProcessingTask) over their profiles and the interactions with the agent.  A KG is used to answer user questions about the exhibition and suggest related items computed using embeddings (ProcessingMethod)

## Visual Task Decomposition
![S7.png](S7.png)

## Terminology 
(dynamic) user questions, behaviors, errors, causes, historical user
data. (static) societal health values, external background knowledge.

## Inference Steps:
1. recollect  events;
2. perceive user actions based on the Virtual Reality action;
3. train a model to compute KG embeddings;
4. rank items to recommend to the user;
5. finally, present the item to the user.

## Tasks 
Recollection (1), Profiling (2), Recommendation (3-4), Communication (5). 

