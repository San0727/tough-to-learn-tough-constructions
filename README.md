# Dataset for Tough to Learn Tough Constructions

This repository contains the datasets used in the paper:

<strong>Tough to Learn Tough Constructions: On the Gap Between Formal and Functional Competence in GPT Models</strong><br>

The datasets were constructed to evaluate large language models’ sensitivity to the syntactic and semantic properties of English *Tough Constructions* using prompt-based acceptability judgment tasks.

---

## Overview

The goal of this dataset is to investigate the potential gap between <strong>formal linguistic competence</strong> (e.g., syntactic well-formedness) and <strong>functional linguistic competence</strong> (e.g., context-sensitive semantic appropriateness) in large language models.

To this end, we designed controlled experimental materials grounded in prior theoretical work on Tough Constructions in English. All sentences and contexts were manually constructed and are not drawn from existing corpora.

---

## Dataset Structure

The repository contains four datasets corresponding to two experiments reported in the paper:

* <strong>Experiment I (Syntax)</strong>
  A syntactic acceptability dataset contrasting Tough Constructions and Subject-Control Constructions, with and without the required gap in the embedded clause.

* <strong>Experiment II (Semantics)</strong>
  Three semantic acceptability datasets testing different contextual sources of difficulty:

  * Object-induced difficulty
  * Goal-induced difficulty
  * Event-induced difficulty

Each dataset consists of multiple item sets designed for prompt-based acceptability judgment tasks.

---

## Experiments

### Experiment I: Syntactic Sensitivity

Experiment I tests whether language models are sensitive to the syntactic constraint that prohibits an overt object in the embedded infinitival clause of Tough Constructions, in contrast to Subject-Control Constructions.

Each item set varies along two dimensions:

* Construction type (Tough vs. Subject-Control)
* Presence vs. absence of a syntactic gap

### Experiment II: Semantic Sensitivity

Experiment II examines whether language models capture context-dependent semantic distinctions among different variants of Tough Constructions, where the source of difficulty arises from:

* the object,
* the goal, or
* the event itself.

For each context, three Tough Construction variants are tested:

* Object-fronted
* Goal-fronted
* It-extraposed

---

## Data Format

Each dataset includes:

* A contextual description (Experiment II only)
* One or more test sentences
* Metadata specifying construction type, context type, and sentence variant

The datasets are formatted for use in prompt-based acceptability judgment tasks employing a 7-point Likert scale.

---

## Usage

These datasets are intended for research purposes. They may be used to:

* Replicate the experiments reported in the paper
* Evaluate other language models on syntactic and semantic acceptability judgments
* Explore the interaction between syntax, semantics, and context in model behavior

When using these materials, please ensure that the experimental design and theoretical assumptions are appropriately acknowledged.

---

## Citation

If you use this dataset, please cite the following paper:

> [Authors]. (Year). *Tough to Learn Tough Constructions: On the Gap Between Formal and Functional Competence in GPT Models*.

(Details to be updated upon publication.)

---

## License

This dataset is released for non-commercial research use. Please see the LICENSE file for details.
