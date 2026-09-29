<img src="assets/profile-portrait.jpg" alt="Portrait of Amirhossein Esbati" width="150" align="right">

# Amirhossein Esbati

I work on **AI/LLM applications where outputs must be inspectable and actions must be reviewable**. My portfolio focuses on evaluation, retrieval, governed analytics, document workflows, and the engineering needed to make those systems usable.

Start with the projects below. Each includes a local setup guide, architecture notes, tests, and an evaluation or implementation-status report. Bundled data are synthetic; connected model and provider results are identified separately.

## Start here

| Project | Engineering question it explores | Evidence |
| --- | --- | --- |
| [EvalBoard](https://github.com/Amirhosseinesbati/evalboard) | How can two AI configurations be compared on the same versioned cases, with failures and missing pairs visible? | [Evaluation protocol](https://github.com/Amirhosseinesbati/evalboard/blob/main/docs/EVALUATION.md) |
| [DataTalk](https://github.com/Amirhosseinesbati/datatalk) | How can natural-language analytics expose metric definitions, bounded SQL, and workspace-scoped results? | [Evaluation protocol](https://github.com/Amirhosseinesbati/datatalk/blob/main/docs/EVALUATION.md) |
| [SupportPilot](https://github.com/Amirhosseinesbati/supportpilot) | How can support answers cite source passages while returns and ticket actions stay under review? | [Evaluation protocol](https://github.com/Amirhosseinesbati/supportpilot/blob/main/docs/EVALUATION.md) |
| [InvoiceLens](https://github.com/Amirhosseinesbati/invoicelens) | How can document extraction keep source evidence, exceptions, and exact-version approvals visible? | [Measured OCR review](https://github.com/Amirhosseinesbati/invoicelens/blob/main/docs/EVALUATION.md) |

<p>
  <a href="https://github.com/Amirhosseinesbati/evalboard"><img src="https://raw.githubusercontent.com/Amirhosseinesbati/evalboard/main/docs/screenshots/04-comparison-1440.png" alt="EvalBoard paired comparison interface" width="32%"></a>
  <a href="https://github.com/Amirhosseinesbati/datatalk"><img src="https://raw.githubusercontent.com/Amirhosseinesbati/datatalk/main/apps/web/screenshots/evidence-sql-1440.jpg" alt="DataTalk answer with inspectable SQL" width="32%"></a>
  <a href="https://github.com/Amirhosseinesbati/supportpilot"><img src="https://raw.githubusercontent.com/Amirhosseinesbati/supportpilot/main/apps/web/screenshots/02-source-passage.png" alt="SupportPilot source passage and answer" width="32%"></a>
</p>

## Model training and MLOps

- [Persian NER with ParsBERT and LoRA](https://github.com/Amirhosseinesbati/parsbert-ner-lora-binary) — parameter-efficient fine-tuning, data versioning, experiment tracking, and API serving.
- [Face Mask Detection](https://github.com/Amirhosseinesbati/FaceMaskDetection) — object detection, training pipeline, experiment tracking, and containerized serving.

## More application work

| Area | Projects |
| --- | --- |
| Document and finance operations | [InvoiceOps](https://github.com/Amirhosseinesbati/invoiceops) · [QuoteFlow](https://github.com/Amirhosseinesbati/quoteflow) |
| Customer operations | [VoiceDesk](https://github.com/Amirhosseinesbati/voicedesk) · [LeadOps](https://github.com/Amirhosseinesbati/leadops) · [ClientLaunch](https://github.com/Amirhosseinesbati/clientlaunch) |
| Editorial workflows | [ContentStudio](https://github.com/Amirhosseinesbati/contentstudio) |
| Domain-specific retrieval | [Mahdaviat Assistant](https://github.com/Amirhosseinesbati/mahdaviatAssistant) |

The portfolio repositories are pilots and research builds. A passing fixture suite demonstrates the workflow under its stated conditions; it is not a claim of live-model quality or production deployment. Each project's evaluation and implementation-status pages describe what was measured and what remains to verify.
