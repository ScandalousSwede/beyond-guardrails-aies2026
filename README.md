# Beyond Guardrails

**Dual Failure Modes in LLM Safety as Inverse Control-System Errors**  
Ethan Gillese · AIES 2026 · Non-archival conference paper

[Read the paper](docs/Beyond_Guardrails_AIES2026_Gillese.pdf) · [Publication page](https://scandalousswede.github.io/beyond-guardrails-aies2026/) · [Citation metadata](CITATION.cff)

Conversational AI can fail by reinforcing harmful premises. It can also fail by dismissing a person's valid cultural, spiritual, identity-based or therapeutic context. This paper asks how safety systems can address both without treating stronger restriction as a complete solution.

The contribution is a conceptual framework supported by retrospective qualitative case analysis. It connects conversational safety, epistemic authority and feedback control; it does not present a trained safety controller or a controlled evaluation of one.

## The two failure modes

| | Mode 1: sycophantic validation | Mode 2: rigid pathologization |
| --- | --- | --- |
| Observed pattern in the paper's cases | Uncritical agreement amplifies harmful or distorted premises. | Authoritative dismissal invalidates a user's contextual framework. |
| Epistemic error proposed by the framework | Deferring too much authority to the user's premises. | Claiming too much authority over the user's meaning-making. |
| Control-system interpretation | Excess positive feedback with insufficient damping. | Excess corrective force or an incorrectly inferred user state. |

The proposed response is **calibrated epistemic humility**: choosing an appropriate degree of assertion, qualification, clarification, correction, assistance or refusal as context changes. The framework is broader than an answer/refuse classifier; a legitimate refusal or clarification is not, by itself, a Mode 2 failure.

## What the paper contributes

- **A shared analytic framework.** It treats the two patterns as related calibration failures, while acknowledging prior work on sycophancy, over-refusal and their pairing.
- **A qualitative synthesis.** Eight illustrative cases were selected from approximately 25 candidate incidents using the paper's stated inclusion criteria.
- **Design and research questions.** The paper motivates longitudinal evaluation, attention to cultural context and user agency, and prospective tests of context-sensitive responses.

A further structural analogy connects embodied intelligence's dependence on environmental grounding with conversational systems' need for contextual and epistemic grounding. This is a theoretical analogy, not evidence that a particular robot architecture or biological mechanism produces safe conversation.

## Evidence and limitations

The paper draws on journalism, legal and regulatory material, professional commentary and user reports. These sources have different evidential strengths. They support examination of reported patterns, not a representative estimate of how often either failure occurs.

The study is retrospective and observational. There was no experimental manipulation of a model, no inter-rater reliability test, and no systematic comparison establishing that one provider is safer than another. Case selection differs between modes; apparent differences in users or narrators may reflect that sampling. Some reports lack complete context or exact model versions.

The dynamical formulation is an explanatory model, not a fitted or independently validated account of users' psychological states. Causal effects of safety training and the effectiveness of proposed mitigations remain questions for prospective research.

See **Methodology**, **Formal Framework** and **Limitations** in the [full paper](docs/Beyond_Guardrails_AIES2026_Gillese.pdf) for the original scope and argument.

## Publication and citation

Accepted for the AAAI/ACM Conference on AI, Ethics, and Society (**AIES 2026**), Malmö, Sweden, October 12–14, 2026; submission **908**. This repository preserves the public **non-archival camera-ready version**. It is not a journal acceptance record, and no journal status is implied.

> Gillese, E. (2026). *Beyond Guardrails: Dual Failure Modes in LLM Safety as Inverse Control-System Errors*. AIES 2026, Malmö, Sweden. Non-archival conference paper. https://scandalousswede.github.io/beyond-guardrails-aies2026/

[CITATION.cff](CITATION.cff) supplies machine-readable metadata for this version. No DOI is assigned in these repository metadata.

## Repository and local preview

| File | Purpose |
| --- | --- |
| [docs/Beyond_Guardrails_AIES2026_Gillese.pdf](docs/Beyond_Guardrails_AIES2026_Gillese.pdf) | Public camera-ready paper |
| [docs/index.html](docs/index.html) | Static publication landing page |
| [CITATION.cff](CITATION.cff) | Preferred paper citation |

To preview the existing publication page locally:

```sh
git clone https://github.com/ScandalousSwede/beyond-guardrails-aies2026.git
cd beyond-guardrails-aies2026
python3 -m http.server 8000 --directory docs
```

Open http://localhost:8000/. Python 3 is sufficient; there is no package installation or frontend build. Expected output is the publication page with a working link to the PDF. Stop the preview with Ctrl+C.

This is a publication repository. It does not contain an executable experiment, a raw case dataset or an automated scientific-validation suite.

## Rights and contact

The paper retains its own copyright notice. This repository currently has no separate open-source licence; public availability does not itself grant unrestricted reuse. Refer to the cited original sources for their rights and context.

Questions or corrections: [egillese@ualberta.ca](mailto:egillese@ualberta.ca).
