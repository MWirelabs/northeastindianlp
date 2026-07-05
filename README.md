# Northeast India NLP Catalog

`Models • Datasets • Speech • OCR • MT • Embeddings • LLMs • Tools`

Inspired by the [Indic NLP Catalog](https://github.com/AI4Bharat/indicnlp_catalog), this repository aims to provide a community-maintained catalog of NLP resources for Northeast India's indigenous languages.

Raise a PR or issue to add resources. See [CONTRIBUTING.md](CONTRIBUTING.md) for entry format and rules.

## Contents

- [Tools and Libraries](#tools-and-libraries)
- [Models](#models)
  - [Pre-trained Language Models](#pre-trained-language-models)
  - [Embedding Models](#embedding-models)
  - [Translation Models](#translation-models)
  - [Speech Models](#speech-models)
  - [Language Identification](#language-identification)
- [Corpora](#corpora)
  - [Speech Corpora](#speech-corpora)
  - [POS Tagged Corpora](#pos-tagged-corpora)
  - [NER Corpora](#ner-corpora)
- [Datasets](#datasets)
- [Evaluation Benchmarks](#evaluation-benchmarks)
- [Applications](#applications)

## Tools and Libraries

- [NE-Agent](https://github.com/MWirelabs/ne-agent) (MWire Labs): Terminal-based multilingual AI agent for NE languages, with retrieval, translation, and transcription. `pip install ne-agent`.
- [NagaNLP](https://arxiv.org/abs/2512.12537): Open-source toolkit for bootstrapping NLP for Nagamese Creole, with human-in-the-loop synthetic data generation.

## Models

### Pre-trained Language Models

- [KhasiBERT](https://huggingface.co/MWirelabs/khasibert) (MWire Labs): Foundational masked language model for Khasi.
- [GaroBERT](https://huggingface.co/MWirelabs) (MWire Labs): Pre-trained language model for Garo.
- [MizoBERT](https://huggingface.co/MWirelabs) (MWire Labs): Pre-trained language model for Mizo.
- [KokborokBERT](https://arxiv.org/abs/2604.19778) (MWire Labs): Pre-trained language model for Kokborok.
- [NyishiBERT](https://huggingface.co/MWirelabs) (MWire Labs): Pre-trained language model for Nyishi.
- [NE-BERT](https://huggingface.co/MWirelabs) (MWire Labs): Multilingual BERT for Northeast Indian languages. Accepted at LoResLM/EACL.
- [MeiteiRoBERTa](https://huggingface.co/MWirelabs) (MWire Labs): RoBERTa-based model for Meitei. Accepted at SIGTYP/EACL.
- [EM-ALBERT](http://catalog.elra.info/en-us/repository/browse/ELRA-W0316/): First ALBERT model for Manipuri, trained on 1,034,715 Manipuri sentences.
- [AxomiyaBERTa](https://huggingface.co/Abhijnan/AxomiyaBERTa): ALBERT-based phonologically-aware model for Assamese, SOTA on AsNER and Cloze-QA.
- [MizBERT](https://huggingface.co/): BERT-based masked language model for Mizo, 98.92% text classification accuracy.
- [NagaLLaMA](https://arxiv.org/abs/2512.12537): Llama-3.2-3B fine-tuned for Nagamese conversation, part of the NagaNLP toolkit.

### Embedding Models

- [NE-Embed](https://huggingface.co/MWirelabs/ne-embed) (MWire Labs): Multilingual sentence embeddings for 10 Northeast Indian languages, fine-tuned from LaBSE.
- [NE-SpeechEmbed](https://huggingface.co/MWirelabs/ne-speechembed) (MWire Labs): Dual-encoder speech-text retrieval model for 8 NE languages.
- [EM-FT](http://catalog.elra.info/en-us/repository/browse/ELRA-W0316/): First FastText word embedding for Manipuri, trained on 1,880,035 sentences.

### Translation Models

- [KokborokMT](https://arxiv.org/abs/2604.19778) (MWire Labs): Machine translation model for Kokborok.

### Speech Models

- [NE-ASR](https://huggingface.co/MWirelabs/ne-asr) (MWire Labs): Fine-tuned Whisper-medium ASR for 8 NE languages.

### Language Identification

- [NE-LID](https://huggingface.co/MWirelabs/ne-lid) (MWire Labs): fastText-based language identification for 11 NE languages, 99.09% accuracy. Published at WiLDRe8/LREC-COLING.

## Corpora

### Speech Corpora

- [northeast-india-voices](https://huggingface.co/datasets/MWirelabs/northeast-india-voices) (MWire Labs): Proprietary speech corpus, 34,500 utterances across Khasi, Nagamese, Mizo, Kokborok, Garo.

### POS Tagged Corpora

- [Tham Khasi Corpus](http://catalog.elra.info/en-us/repository/browse/ELRA-W0321/#): Annotated Khasi POS tagged corpus, 83,312 words, 4,386 sentences.
- [KMI Linguistics Bodo](https://github.com/kmi-linguistics/bodo): Bodo corpus and frequency-ordered word/punctuation list.

### NER Corpora

- [AsNER](https://arxiv.org/ftp/arxiv/papers/2207/2207.03422.pdf): Named entity annotation dataset for Assamese, 99k tokens.

## Datasets

- [Northeast India Districts and Villages](https://huggingface.co/datasets/MWirelabs/Northeast-India-Districts-and-Villages) (MWire Labs): ~49,275 rows of district/village data, cleaned from LGDirectory (Government of India).
- [Ema-lon Manipuri Corpus](http://catalog.elra.info/en-us/repository/browse/ELRA-W0316/): Manipuri-English comparable corpus, up to 1.88M Manipuri sentences, 1.45M English sentences.

## Evaluation Benchmarks

- NortheastBench-Speech (MWire Labs): 8,099-utterance evaluation benchmark for NE speech tasks.

## Applications

- [NE-Agent](https://github.com/MWirelabs/ne-agent) (MWire Labs): Multilingual terminal agent with retrieval, translation, and transcription for NE languages.

---

*Under active construction. Contributions welcome.*
