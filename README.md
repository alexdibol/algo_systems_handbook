# ALGORITHMIC TRADING SYSTEMS LAB

## Five Agentic Architectures Across Equities, Oil Futures, FX Carry, Credit, and Volatility

Author: Alejandro Reynoso

---

## Overview

This repository contains the **Algorithmic Trading Systems Lab**, a research and implementation collection built around five governance-first agentic trading architectures.

The repository includes:

1. Five academic papers  
2. One consolidated handbook  
3. Five corresponding Google Colab notebooks  

The five papers cover:

1. Equities  
2. Oil Futures  
3. FX Carry  
4. Credit  
5. Volatility  

The purpose of the Lab is to show that algorithmic trading is not merely a matter of prediction, signal generation, or backtested performance. A serious trading system is a designed institutional architecture. It must preserve data lineage, make assumptions explicit, bound the role of agents, expose its gates to inspection, produce auditable outputs, and keep final recommendations subject to human accountability.

The Lab therefore treats algorithmic trading as a problem of **governed system design**.

---

## Why This Lab Matters

The Algorithmic Trading Systems Lab is a fundamental piece in the learning ladder of algorithmic trading because it occupies the space between abstract theory and serious implementation.

Many students and practitioners learn trading models as isolated techniques: a signal, a classifier, a backtest, a portfolio rule, or an optimization routine. Those tools are useful, but they are not enough. A trading system that cannot explain its evidence, preserve its assumptions, document its failures, survive stress tests, and generate reviewable artifacts is not yet an institutional system.

This Lab addresses that gap.

It teaches that algorithmic trading requires more than a model. It requires an architecture. That architecture must coordinate data, features, regimes, agents, controls, costs, stress tests, reports, and human review. The model is only one component inside a broader workflow. The deeper question is not simply whether the model can produce an attractive result. The deeper question is whether the entire process can be reconstructed, challenged, defended, audited, and improved.

For that reason, the Lab is not just a collection of papers and notebooks. It is a learning system. The papers establish the conceptual and market-specific designs. The notebooks make the ideas executable. The handbook provides the consolidated map that explains how the five architectures belong to a single governance-first discipline.

---

## The Learning Ladder

This repository is designed as a bridge across several stages of learning.

At the first stage, the reader learns that algorithmic trading is not simply signal discovery. It is system design.

At the second stage, the reader learns that each market has a different trading surface. Equities, oil futures, FX carry, credit, and volatility do not present the same evidence, the same risks, the same execution problems, or the same failure modes.

At the third stage, the reader learns that serious trading systems require governed workflows. Data must be validated. Regimes must be inferred carefully. Agents must have bounded roles. Recommendations must be stress-tested. Outputs must be auditable.

At the fourth stage, the reader moves from conceptual understanding to implementation. The Colab notebooks translate the architecture into executable workflows with synthetic data, agent definitions, state management, regime classification, stress testing, audit artifacts, and readable reports.

At the fifth stage, the reader begins to think architecturally. The five capstones are different on the surface, but they share a deeper structure: each contains a trading object, an evidence layer, a validation layer, a regime layer, a specialized-agent layer, a coordination layer, a control layer, a stress layer, an audit layer, and a human review layer.

That shift, from learning isolated models to understanding governed trading architectures, is the central educational purpose of the Lab.

---

## The Handbook

The handbook consolidates the five capstone studies into a single guide.

It provides the conceptual map for the repository. Its role is not merely to summarize the papers, but to explain the common architecture that connects them.

The handbook develops the central thesis that algorithmic trading systems must be governed from the first architectural decision. It explains why data lineage must be preserved, why assumptions must be explicit, why agents must be bounded, why gates must be inspectable, why outputs must be auditable, and why final recommendations must remain subject to human accountability.

The handbook also explains why different markets require different system designs. Equities, oil futures, FX carry, credit, and volatility each require a different model of evidence, risk, regime behavior, and execution. Yet all five systems share a common institutional logic: each combines deterministic components, statistical inference, generative AI interpretation, and human review into a controlled workflow.

The handbook is therefore the intellectual center of the repository. It shows how the five papers and five notebooks form a unified laboratory for algorithmic trading as an auditable, hybrid, agentic, and governance-first discipline.

---

## The Five Papers

### 1. Equities

The equities paper develops an **agentic architecture for listed equity trading**.

Equities are the natural introductory market for the Lab because they force the system to work with both numerical and narrative evidence. The trading surface includes prices, returns, volumes, spreads, volatility, liquidity, sector structure, news flow, analyst commentary, social attention, and sentiment. A serious equity system cannot simply observe a stock price and produce a signal. It must understand the environment in which that signal appears.

The agentic architecture in the equities paper is designed as a governed research organization. One set of agents defines the admissible universe, collects or generates structured market data, and validates the quality and lineage of that evidence. Other agents interpret unstructured information, extract bounded sentiment, measure social attention, classify regimes, generate signals, construct portfolios, estimate transaction costs, run stress tests, and prepare audit-ready reports.

This architecture is important because equity evidence is heterogeneous. Price data, liquidity data, factor behavior, firm-specific news, and market narratives all have different failure modes. The system therefore must coordinate different forms of evidence without allowing any single agent, model, or backtest to dominate the final recommendation.

The equities paper focuses on:

* structured market data;
* unstructured narrative information;
* sentiment and social attention;
* regime-aware signal interpretation;
* universe selection and mandate definition;
* portfolio construction under sector, name, turnover, and liquidity limits;
* transaction-cost and execution realism;
* stress testing under liquidity shocks, gap events, crowding, and narrative reversals;
* audit reporting and committee-readable decision packages.

The equities architecture teaches that stock trading is not merely stock selection. It is the construction of a controlled evidence workflow in which every recommendation must be traceable, stress-tested, and accountable.

---

### 2. Oil Futures

The oil futures paper develops an **agentic architecture for curve-aware oil futures trading**.

Oil futures cannot be reduced to a one-price forecasting problem. Oil is physical, financial, geopolitical, and macroeconomic at the same time. Its price reflects production, inventories, refinery demand, storage economics, transportation constraints, geopolitical shocks, OPEC policy, macro expectations, and financial positioning.

The trading surface is the futures curve. Front-month, short-dated, medium-dated, and long-dated contracts may carry different information. The front end of the curve may express immediate scarcity, storage pressure, logistical stress, or inventory imbalance. Deferred contracts may reflect medium-term expectations, macro demand, financing conditions, and longer-term equilibrium views. Contango, backwardation, roll yield, curve steepening, curve flattening, and supply shocks are therefore central to the trading logic.

The agentic architecture in the oil paper is built around maturity-specific reasoning. The system does not collapse the entire curve into one crude oil price. Instead, it assigns bounded analytical roles to agents that evaluate different parts of the curve, validate roll conventions, interpret contract-level valuation, estimate carry, coordinate outright or spread positions, allocate risk capital, test liquidity and margin implications, and prepare audit records.

This architecture matters because oil futures strategies often fail when the system ignores the structure of the curve. A trade can appear attractive in a simplified price series while disappearing once roll cost, maturity identity, open interest, margin requirements, execution timing, and stress dislocations are incorporated.

The oil futures paper focuses on:

* the physical and financial structure of oil markets;
* futures term structure;
* contango and backwardation;
* roll yield and roll-risk discipline;
* inventory pressure and supply-shock regimes;
* maturity-specific valuation agents;
* curve-based allocation;
* execution-cost and liquidity realism;
* stress testing under geopolitical shocks, storage saturation, demand collapse, and forced rolling;
* committee reporting for curve posture and unresolved risks.

The oil architecture teaches that serious algorithmic trading must begin by defining the trading object correctly. In oil futures, the object is not simply the price of crude oil. It is the governed curve.

---

### 3. FX Carry

The FX paper develops an **agentic architecture for FX carry and relative-value currency trading**.

FX carry is one of the canonical examples of systematic macro trading, but it is also one of the most dangerous when misunderstood. The simple intuition is to borrow in low-yielding currencies and invest in high-yielding currencies. The institutional reality is much more complex. Carry returns combine interest-rate differentials, spot exchange-rate movements, volatility, funding-currency behavior, liquidity, transaction costs, financing assumptions, and regime risk.

The trading surface is relative. Currencies are not bought in isolation. They are bought against other currencies. The system must therefore evaluate long-leg candidates, funding-leg candidates, pair construction, basket concentration, financing drag, safe-haven rally risk, and carry-unwind vulnerability.

The agentic architecture in the FX paper is designed as a disciplined relative-value desk. A synthetic FX macro-data agent creates synchronized spot series, rate paths, volatility measures, funding conditions, and event regimes. A data-quality and lineage agent checks timestamp alignment, rate conventions, carry calculations, financing assumptions, and internal coherence. A regime agent classifies environments such as carry-harvest, unstable transition, and unwind stress. Currency-level agents then evaluate each currency as both a potential long leg and a potential funding leg. Pair-construction and basket-coordination agents convert those local currency assessments into governed exposure.

This separation between currency evaluation, pair construction, and basket coordination is a governance choice. It prevents the system from mechanically converting a top-versus-bottom ranking into a trade regardless of funding pressure, correlation, liquidity, or regime fragility.

The FX paper focuses on:

* the economics of carry;
* funding currencies and investment currencies;
* interest-rate differentials;
* spot risk and safe-haven behavior;
* volatility-adjusted carry;
* risk-on, transition, and risk-off regimes;
* pair selection and basket construction;
* carry-unwind risk;
* funding stress and rollover assumptions;
* transaction costs, financing drag, and implementation realism;
* committee reporting for currency exposure and unwind vulnerability.

The FX architecture teaches that carry is not simply the collection of yield. It is a governed exposure to relative value, funding structure, spot behavior, and regime-dependent unwind risk.

---

### 4. Credit

The credit paper develops an **agentic architecture for governed credit-spread trading**.

Credit trading requires taxonomy before architecture. It is not one activity. It may include cash bond carry, spread trading, relative-value quality rotation, rating migration defense, synthetic protection, liquidity defense, and committee-reviewed allocation. The credit capstone focuses on a bounded domain: rating-segmented spread trading across synthetic AAA, AA, and A universes.

The trading surface is spread-sensitive and rating-aware. AAA, AA, and A exposures do not play the same role. AAA credit may function as a quality anchor. AA credit may provide an intermediate layer between defense and return. A-rated exposure may offer richer spread compensation but greater sensitivity to widening, liquidity stress, downgrade risk, and risk-off regimes.

The agentic architecture in the credit paper treats the trading object as a governed spread posture rather than a free-form search for higher yield. A shared state organizes approved universes, spread histories, duration measures, volatility, liquidity metrics, rating buckets, regime probabilities, bucket-level scorecards, proposed allocations, execution assumptions, stress outcomes, and audit records. Data-quality agents check stale marks, inconsistent rating assignments, impossible spreads, duration mismatches, liquidity gaps, and transformations that might obscure widening events. Regime agents classify calm carry, unstable widening, and acute stress. Bucket-level agents evaluate whether additional spread compensation is justified by the associated liquidity, volatility, migration, and stress risk.

This architecture matters because credit can appear precise while being fragile. Marks may be stale. Liquidity may vanish exactly when the system needs to trade. A spread premium may look attractive until downgrade risk, dealer-balance-sheet pressure, duration exposure, and stress widening are incorporated. The agentic design therefore forces each recommendation to pass through taxonomy, evidence validation, regime classification, bucket-level analysis, deterministic limits, stress testing, audit preservation, and committee review.

The credit paper focuses on:

* credit-spread behavior;
* rating-segmented universes;
* AAA, AA, and A bucket differentiation;
* spread widening and compression regimes;
* carry versus downgrade and migration risk;
* liquidity risk and stale-price discipline;
* duration and spread-volatility effects;
* defensive rotation and abstention under unstable regimes;
* stress testing under widening, downgrade, liquidity, and dealer-balance-sheet shocks;
* credit committee-style reporting.

The credit architecture teaches that credit trading is not the mechanical purchase of additional yield. It is the governed evaluation of spread compensation under regime uncertainty, liquidity friction, rating migration, and institutional accountability.

---

### 5. Volatility

The volatility paper develops an **agentic architecture for trading and governing derivatives Greeks**.

Volatility trading requires a different conceptual frame from ordinary directional trading. The system is not primarily choosing whether an asset price goes up or down. It is managing exposure geometry. Delta, Gamma, Vega, Theta, and Rho define different dimensions of sensitivity, and those sensitivities change across regimes, surfaces, paths, and time.

The relevant trading surface includes the option universe, underlying-price histories, interest-rate assumptions, dividend assumptions where relevant, implied-volatility surfaces, realized-volatility behavior, liquidity indicators, current portfolio holdings, computed Greeks, target exposure geometry, execution candidates, stress results, and audit artifacts. Sensitivity is not merely a number. In a governed architecture, each Greek is an artifact with provenance.

The agentic architecture in the volatility paper behaves like a governed sensitivity desk. Deterministic pricing and risk engines calculate primary Greeks. Volatility-surface agents record level, slope, skew, and term structure. Realized-volatility modules track what the underlying has actually done. Data-quality and lineage agents check stale quotes, inconsistent strikes, missing expiries, implausible implied volatilities, broken parity relationships, unstable surface fits, and abrupt Greek changes caused by bad data rather than real economic movement. Regime agents classify volatility environments. Greek-specific agents interpret Delta, Gamma, Vega, Theta, and Rho in context. A coordinator turns those interpretations into a target exposure geometry, while risk agents constrain, stress, and document the proposal.

This architecture matters because derivatives books can change character when markets move. Greeks are local approximations. A book that looks well-behaved under today’s surface may become unstable after a spot gap, volatility spike, volatility crush, skew twist, term-structure shift, time passage, or rate shock. The system therefore must recalculate sensitivities under stress rather than relying only on static pre-shock Greeks.

The volatility paper focuses on:

* Delta exposure;
* Gamma convexity;
* Vega and implied-volatility sensitivity;
* Theta decay;
* Rho and rate sensitivity;
* volatility regimes;
* implied-volatility surfaces;
* realized-volatility behavior;
* nonlinear exposure geometry;
* execution feasibility and re-hedging costs;
* stress testing under spot, volatility, skew, term-structure, time, and rate shocks;
* committee-readable derivatives risk reporting.

The volatility architecture teaches that derivatives trading should not be governed by strategy names alone. A straddle, calendar spread, collar, or hedge is only a packaging choice. What matters institutionally is the exposure geometry, the regime in which that geometry is held, the cost of maintaining it, and the stress behavior that reveals how it can fail.

---

## Colab Notebooks

Each paper is accompanied by a corresponding Google Colab notebook.

The notebooks translate the conceptual architectures into executable educational workflows. They allow the reader to move from theory to implementation by showing how a governed agentic trading system can be structured in code.

The notebooks may include:

* synthetic data generation;
* agent definitions;
* shared-state architecture;
* regime classification;
* signal generation;
* portfolio or exposure construction;
* transaction-cost modeling;
* stress testing;
* audit artifacts;
* readable reports.

The notebooks are not intended to be production trading systems. They are educational implementations designed to make the architecture visible, testable, and extensible.

---

## Core Design Principle

The repository is built around one central principle:

**The model proposes, governance challenges, audit evaluates, and the human remains accountable.**

These systems do not present generative AI as an autonomous trader. Instead, generative AI is used as a bounded interpretive layer inside a broader architecture of deterministic controls, statistical methods, audit logs, stress tests, and human review.

The hard-coded components perform tasks that require precision and reproducibility. The statistical components infer regimes and uncertainty. The generative AI components interpret bounded evidence and draft readable explanations. The human reviewer remains responsible for approval, rejection, escalation, or revision.

---

## Common Architecture Across the Lab

Although each paper studies a different market, the five architectures share a common workflow:

1. Define the market and trading surface.
2. Generate or acquire evidence.
3. Validate evidence before downstream use.
4. Infer the relevant market regime.
5. Assign specialized agents to bounded analytical roles.
6. Convert local analysis into a coordinated portfolio or exposure recommendation.
7. Apply deterministic constraints and risk limits.
8. Adjust for transaction costs, liquidity, slippage, financing, or execution realism.
9. Stress the recommendation under adverse scenarios.
10. Evaluate performance and robustness.
11. Preserve artifacts, logs, prompts, outputs, warnings, and reports.
12. Produce a committee-readable decision package.
13. Require human review before approval.

This common architecture is what makes the Lab more than a collection of separate market studies. It is a unified framework for thinking about algorithmic trading systems as governed, auditable, agentic workflows.

---

## Educational Purpose

This repository is intended for:

* students of algorithmic trading;
* finance professionals;
* quantitative researchers;
* AI governance practitioners;
* model-risk reviewers;
* instructors teaching AI and finance;
* practitioners interested in agentic trading-system design.

The repository is educational and research-oriented. Its purpose is to help readers understand how trading systems can be designed, implemented, reviewed, challenged, and improved.

The Lab does not teach automation for its own sake. It teaches disciplined augmentation. It shows how deterministic code, statistical inference, generative AI, and human judgment can be combined into systems that are more transparent, more testable, and more institutionally serious.

---

## License

MIT License

Copyright (c) 2026 Alejandro Reynoso

Permission is hereby granted, free of charge, to any person obtaining a copy of this repository and associated documentation files, notebooks, code, and educational materials (the "Materials"), to deal in the Materials without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or adapt copies of the Materials, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Materials.

The Materials are provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, non-infringement, accuracy, completeness, or suitability for any trading, investment, financial, academic, professional, or institutional purpose. In no event shall the author or copyright holder be liable for any claim, damages, losses, liabilities, costs, or expenses arising from, out of, or in connection with the Materials or the use or other dealings in the Materials.

---

## Disclaimer

This repository is provided for educational, research, and instructional purposes only.

Nothing in the papers, handbook, notebooks, examples, code, reports, diagrams, or related materials constitutes investment advice, financial advice, trading advice, legal advice, tax advice, accounting advice, compliance advice, or a recommendation to buy, sell, hold, hedge, structure, or trade any financial instrument, security, derivative, currency, commodity, credit exposure, volatility position, or portfolio.

The systems described in this repository are conceptual, pedagogical, and experimental. They are designed to illustrate governance-first algorithmic trading architectures, agentic workflows, synthetic data generation, regime-aware analysis, auditability, stress testing, and committee-readable reporting. They are not production trading systems and should not be relied upon for live trading, portfolio management, risk management, or investment decision-making.

Any real-world implementation would require independent validation, professional review, model-risk assessment, legal and compliance approval, operational testing, cybersecurity review, data-quality verification, financial-risk analysis, and appropriate human oversight.

Generative AI was used as an assistant in portions of the coding, drafting, writing, editing, structuring, and explanatory development of these materials. However, the author retains full responsibility for the conception, design, editorial judgment, technical review, final content, and publication of the repository. Generative AI was used as a supporting tool, not as an autonomous author, researcher, trader, investment adviser, or decision-maker.

All editorial control, technical control, methodological responsibility, and final accountability remain with the author.

The materials may contain simplifications, synthetic examples, illustrative assumptions, simulated data, pedagogical abstractions, and experimental workflows. Users are responsible for reviewing, testing, validating, and adapting any material before relying on it for any purpose. No representation is made that the methods, code, models, workflows, or reports are accurate, complete, current, robust, profitable, compliant, or suitable for any particular use case.

By using this repository, users acknowledge that they do so at their own risk.


---
## Citation

```text
Reynoso, Alejandro. Algorithmic Trading Systems Lab: Five Agentic Architectures Across Equities, Oil Futures, FX Carry, Credit, and Volatility.
```
