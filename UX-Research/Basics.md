Deductive Reasoning 
for descriptive or causal research

- problem
- hypothesis
- variables
	dependent : value being measured, user satisfaction
	independent : manipulated value that influenced dependent variable, colour
	control : confounding variable, tech saviness

Inductive Reasoning
for exploratory research

- interviews

# Diagram

Prior to experimentation form a model to describe the expected relationships between the observed behaviours and triggers. This representation helps outline the experimental design.

Update the model as experiment data comes in.

```mermaid
flowchart LR
	subgraph IV
		direction TB
		A(Learnability) -.- B(Memorability)
	end
	subgraph Primary-DV
		direction TB
		C(Effectiveness) -.- D(Efficiency)
	end
	subgraph Secondary-DV
		direction TB
		E(Satisfaction) -.- F(Performance)
	end
	subgraph CV
		G((Familiarity))
	end
	IV --> Primary-DV --> Secondary-DV
	CV --> Primary-DV
```

# Reasoning

Deductive vs Inductive reasoning.

|Reasoning|Begin With|Use For|Method|Process|Answers|
|--|--|--|--|--|--|
|Deductive|Theory / Model|Testing|Quantitative|Objective|Who/What|
|Inductive|Phenomenae|Exploring|Qualitative|Subjective|How/Why|
