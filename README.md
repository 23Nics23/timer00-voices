# Timer00 – coach voices

Neural text-to-speech voices (Piper, ONNX) used by the Timer00 iPhone app for the
workout coach. The app downloads one voice the first time a coach language is used.
The files are attached to the GitHub releases of this repository; they are unchanged
copies of the original models.

| File | Language | Source | License |
|---|---|---|---|
| it_IT-serena-high | Italian | [committa/it_IT-serena-high](https://huggingface.co/committa/it_IT-serena-high) (dataset committa/serena-synthetic-it-28h, Qwen3-TTS synthetic) | CC BY 4.0 |
| en_US-kathleen-medium | English | [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices) (OHF-Voice voice-datasets) | CC0 |
| es_ES-sharvard-medium | Spanish | [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices) (Sharvard Corpus, speaker F) | CC BY 3.0 |
| fr_FR-siwis-medium | French | [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices) (SIWIS French Speech Synthesis Database) | CC BY 4.0 |
| de_DE-kerstin-medium | German | [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices) (OHF-Voice voice-datasets) | CC0 |
| nl_BE-nathalie-medium | Dutch | [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices) (OHF-Voice voice-datasets) | CC0 |
| pl_PL-gosia-medium | Polish | [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices) (OHF-Voice voice-datasets) | CC0 |

Several voices are fine-tuned from the Hi-Fi Multi-Speaker English TTS Dataset
(NVIDIA, CC BY 4.0), reader 92. Each voice's original model card is attached to the
release next to the model (`*.MODEL_CARD.md`).

Piper: https://github.com/rhasspy/piper (MIT).

## Privacy

Downloading a voice is a plain file download: no personal data is sent. GitHub, which
hosts the files, receives only the IP address needed for the connection.
