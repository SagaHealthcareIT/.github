## Saga IT

Healthcare integration and software development, based in West Palm Beach, Florida.

Since 2016 we have built and supported the interfaces that move clinical and administrative data between hospitals, medical device manufacturers, payers and digital health companies: HL7 v2, FHIR, DICOM imaging and X12 EDI.

Most of what we publish here is tooling for interface engines. We work with the open-source [Mirth Connect](https://saga-it.com/services/mirth-connect) line, [Eclipse Open Integration Engine](https://saga-it.com/services/open-integration-engine) and BridgeLink, and we are an independent commercial support vendor and contributor in the OIE ecosystem.

### Open source

| Project | What it does |
| --- | --- |
| **[mirthsync](https://github.com/SagaHealthcareIT/mirthsync)** | Pulls channels, code templates, the configuration map and global scripts out of an interface engine as plain files, and pushes them back. Interface config becomes reviewable in pull requests, promotable between environments and recoverable. Clojure, EPL-1.0. |
| **[mirthsync-vscode](https://github.com/SagaHealthcareIT/mirthsync-vscode)** | Browse and sync channels from inside VS Code, with IntelliSense for Mirth scripting APIs while editing transformers. |
| **[mirthsync-plugin](https://github.com/SagaHealthcareIT/mirthsync-plugin)** | Runs MirthSync from inside the engine's own Administrator client. Apache-2.0. |
| **[mirthsync-ci](https://github.com/SagaHealthcareIT/mirthsync-ci)** | A worked CI/CD setup for channel promotion using GitHub Actions. |
| **[MirthHL72SQS](https://github.com/SagaHealthcareIT/MirthHL72SQS)** | Sends HL7 messages to AWS SQS from Mirth Connect. |
| **[mirth-loadtest](https://github.com/SagaHealthcareIT/mirth-loadtest)** | Accepts DICOM and generates randomised HL7 and DICOM traffic for load testing. |

Installable builds: [MirthSync CLI](https://saga-it.com/products/mirthsync) · [VS Code extension](https://saga-it.com/products/mirthsync-vscode) · [engine plugin](https://saga-it.com/downloads/mirthsync-plugin)

### Products

- **[Clinical Extract](https://clinicalextract.com)** pulls research data from any EHR with a certified bulk FHIR API (Epic, Oracle Health, athenahealth, eClinicalWorks, MEDITECH, NextGen and Veradigm) and returns one CSV with a data dictionary. It runs in the customer's environment.
- **[Kymolog](https://kymolog.com)** codes bedside and wearable device readings to FHIR R4 with LOINC and UCUM, files them in the EHR and keeps each reading with its device and time for research.

### Free tools

- **[DICOM Viewer](https://saga-it.com/dicom/viewer)** opens imaging studies in the browser, nothing to install and no sign-up.
- **[DICOM Spec Browser](https://saga-it.com/dicom/spec)** is the DICOM standard, cross-linked and searchable, no sign-up.
- **[HL7 Workbench](https://saga-it.com/hl7workbench)** is an HL7 v2 and FHIR spec browser, open to anyone. The message parser and validator need a free account.

### What we do

[Interface engine implementation and support](https://saga-it.com/services/mirth-connect), [Open Integration Engine migrations](https://saga-it.com/services/open-integration-engine), EHR and imaging integration, and custom healthcare software.

[saga-it.com](https://saga-it.com)
