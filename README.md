# Project Prometheus: Compute Where It Matters

## Research question
Can uncertainty-guided allocation of GPU inference achieve comparable ink-detection performance with fewer computational resources than uniform inference configurations?

## Scientific target
Herculaneum papyrus ink detection using the Vesuvius Challenge pretrained model.

## Initial objectives
- Establish a reproducible GPU inference workflow using Fuzzball.
- Measure inference runtime and GPU resource utilization.
- Compare inference configurations across depth windows.
- Evaluate prediction agreement and variability.
- Investigate parallel execution across available GPU resources.

## Experimental principles
- Record configurations and runtime for every run.
- Separate measured results from hypotheses.
- Do not claim improved ink-detection accuracy without independent ground-truth labels.
