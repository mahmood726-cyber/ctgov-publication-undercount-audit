# CT.gov Publication Undercount Audit

## Overview

A standalone E156 project auditing how often CT.gov no-link records still show a PubMed NCT paper trail. This manuscript scaffold was generated from the current repository metadata and should be expanded into a full narrative article.

## Study Profile

Type: methods
Primary estimand: Weighted PubMed NCT-match rate among older CT.gov records lacking linked publications
App: CT.gov Publication Undercount Audit dashboard
Data: Sponsor-class-stratified sample of 1,050 older no-link studies queried against PubMed by NCT ID
Code: https://github.com/mahmood726-cyber/ctgov-publication-undercount-audit

## E156 Capsule

How often do ClinicalTrials.gov records with no linked publication hide an external PubMed trail when searched by NCT identifier? We drew a sponsor-class-stratified audit sample of 1,050 older studies lacking CT.gov publication links from the March 29, 2026 full-registry snapshot. Each sampled NCT identifier was queried against PubMed using identifier-based E-utilities searches, then reweighted back to the sponsor-class distribution of older no-link studies. The weighted PubMed NCT-match rate across the no-link older-study population was only 1.2 percent, indicating that external publication rescue was uncommon on this identifier-based audit. The weighted external-publication-only rate among no-link studies was just 0.3 percent, and the industry sample reached 2.0 percent on the raw PubMed match rate. Missing CT.gov publication links therefore look more like true visible sparsity than widespread under-linking, at least under a strict NCT-indexed external search strategy. This audit is sample-based and identifier-dependent, so it can miss publications that omit NCT identifiers or sit outside PubMed indexing today.

## Expansion Targets

1. Expand the background and rationale into a full introduction.
2. Translate the E156 capsule into detailed methods, results, and discussion sections.
3. Add figures, tables, and a submission-ready reference narrative around the existing evidence object.
