## DCC Data Competence Center
The [DCC](https://www.bs.ch/daten/databs/dcc) at the [Statistical Office](https://statistik.bs.ch/) is the new central point of contact for data within the administration of the Canton of Basel-Stadt. Our specialists support departments of the cantonal administration with their data management.

<a href="https://www.bs.ch/schwerpunkte/daten/databs/schwerpunkte/datenwissenschaften-und-ki"><img src="https://github.com/DCC-BS/.github/blob/main/_imgs/databs_log.png?raw=true" alt="DCC Logo" width="200" /></a>

Data Science and AI <br>
Developed with ❤️ by DCC - Data Competence Center

# Our Open-Source applications, packages and projects:
We publish docker images and docker compose files for all of our AI applications. Additionally, we publish our TypeScript packages on npm and our Python packages on pypi.



## Our Dev Standards & Guidelines
[Here are our Dev Standards & guidelines](https://dcc-bs.github.io/documentation/)

## Other GitHub organizations from Statistisches Amt Basel-Stadt:
* [Statistisches Amt Basel-Stadt](https://github.com/StataBS)
* [Open Data Basel-Stadt](https://github.com/opendatabs)

## Text Mate
Text Mate is a modern web application for advanced text editing, correction, and document validation. Built with Nuxt.js and TypeScript, it provides a rich set of tools to enhance writing experiences.
- [Frontend](https://github.com/DCC-BS/text-mate-frontend)
- [Backend](https://github.com/DCC-BS/text-mate-backend)


## Transcribo
Transcribo is an app for audio/video transcription with timeline-based editing.
- [Frontend](https://github.com/DCC-BS/transcribo-frontend)
- [Backend](https://github.com/DCC-BS/transcribo-backend)


## Report Generator
The Report Generator (Bericht-Generator) is a web app for creating multimedia reports. It offers an intuitive interface to record complaints, add evidence, and generate professional reports.
- [Frontend](https://github.com/DCC-BS/bericht-frontend)
- [Backend](https://github.com/DCC-BS/bericht-backend)

## BS Translator
Translate texts, PDF or Word documents with formatting.
- [Frontend](https://github.com/DCC-BS/bs-translator-frontend)
- [Backend](https://github.com/DCC-BS/bs-translator-backend)



## Docling Plugins

We built three [docling](https://github.com/docling-project/docling) plugins. First, docling-glm-ocr to integrate vLLM remote served [GLM-OCR](https://huggingface.co/zai-org/GLM-OCR) OCR model in a docling pipeline. Second, docling-pp-doc-layout to integrate [PP-DocLayout-V3](https://huggingface.co/PaddlePaddle/PP-DocLayoutV3) layout detection model in a docling pipeline. Third, docling-pp-ocrv6 to integrate the PP-OCRv6 OCR model in a docling pipeline. We also provide various [docling-serve](https://github.com/docling-project/docling-serve) images with the plugins installed and a patched gradio demo.
- [docling-glm-ocr](https://github.com/DCC-BS/docling-glm-ocr)
- [docling-pp-doc-layout](https://github.com/DCC-BS/docling-pp-doc-layout)
- [docling-pp-ocrv6](https://github.com/DCC-BS/docling-pp-ocrv6)
- [dcc-docling-serve](https://github.com/DCC-BS/dcc-docling-serve)

## BentoML Faster Whisper
An OpenAI-compatible Speech-to-Text API built with BentoML and Faster Whisper. It features built-in support for speaker diarization and Voice Activity Detection (VAD).
- [GitHub](https://github.com/DCC-BS/bentoml-faster-whisper)


# Our Libraries


## Python
| Library | Repository | Version |
|---------|------------|---------|
| backend-common | [GitHub](https://github.com/DCC-BS/backend-common) | [![PyPI version](https://img.shields.io/pypi/v/dcc-backend-common.svg)](https://pypi.org/project/dcc-backend-common/) |
| docling-glm-ocr | [GitHub](https://github.com/DCC-BS/docling-glm-ocr) | [![PyPI version](https://img.shields.io/pypi/v/docling-glm-ocr.svg)](https://pypi.org/project/docling-glm-ocr/) |
| docling-pp-doc-layout | [GitHub](https://github.com/DCC-BS/docling-pp-doc-layout) | [![PyPI version](https://img.shields.io/pypi/v/docling-pp-doc-layout.svg)](https://pypi.org/project/docling-pp-doc-layout/) |
| docling-pp-ocrv6 | [GitHub](https://github.com/DCC-BS/docling-pp-ocrv6) | [![PyPI version](https://img.shields.io/pypi/v/docling-pp-ocrv6.svg)](https://pypi.org/project/docling-pp-ocrv6/) |


## Typescript

| Library | Repository | Version |
|---------|------------|---------|
| common-ui.bs.js | [GitHub](https://github.com/DCC-BS/common-ui.bs.js) | ![GitHub package.json version](https://img.shields.io/github/package-json/v/DCC-BS/common-ui.bs.js) |
| event-system.bs.js | [GitHub](https://github.com/DCC-BS/event-system.bs.js) | ![GitHub package.json version](https://img.shields.io/github/package-json/v/DCC-BS/event-system.bs.js) |
| dependency-injection.bs.js | [GitHub](https://github.com/DCC-BS/dependency-injection.bs.js) | ![GitHub package.json version](https://img.shields.io/github/package-json/v/DCC-BS/dependency-injection.bs.js) |
| audio-recorder.bs.js | [GitHub](https://github.com/DCC-BS/audio-recorder.bs.js) | ![GitHub package.json version](https://img.shields.io/github/package-json/v/DCC-BS/audio-recorder.bs.js) |
| communication.bs.js | [GitHub](https://github.com/DCC-BS/communication.bs.js) | ![GitHub package.json version](https://img.shields.io/github/package-json/v/DCC-BS/communication.bs.js) |

# Nuxt Layers
Nuxt layers allow you to extend and share configurations, components, composables, and assets across multiple Nuxt applications. 

### Why Nuxt Layers are useful:
- **Code Reuse**: Write once, reuse everywhere. Standard components, layouts, and logic can be easily shared.
- **Maintainability**: Update common utilities or UI patterns in a single place to propagate changes across all dependent projects.
- **Modular Architecture**: Build clean, decoupled, and focused feature modules that can be composed into larger applications.

- [GitHub Repository](https://github.com/DCC-BS/nuxt-layers)

