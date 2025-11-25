# Podcawise TTS Models

ONNX model files for Chatterbox Multilingual TTS engine used by Podcawise - Desktop AI Podcast Studio.

## Supported Languages (23)

Arabic, Danish, German, Greek, English, Spanish, Finnish, French, Hebrew, Hindi, Italian, Japanese, Korean, Malay, Dutch, Norwegian, Polish, Portuguese, Russian, Swedish, Swahili, Turkish, Chinese

## Files

This repository hosts the following model files in [Releases](https://github.com/seed-blocks/podcawise-models/releases):

### v1.1.0 - Multilingual (Recommended)

- `speech_encoder.onnx` / `speech_encoder.onnx_data`
- `embed_tokens.onnx` / `embed_tokens.onnx_data`
- `language_model_q4.onnx` / `language_model_q4.onnx_data` (INT4 quantized)
- `conditional_decoder.onnx` / `conditional_decoder.onnx_data`
- `tokenizer.json`
- `Cangjie5_TC.json` (Chinese character mapping)

Total download size: ~1.5GB

### v1.0.0 - English Only (Legacy)

English-only version for smaller footprint if multilingual support is not needed.

## Source

Models are sourced from [onnx-community/chatterbox-multilingual-ONNX](https://huggingface.co/onnx-community/chatterbox-multilingual-ONNX) on Hugging Face.

## License

The models are distributed under their original license terms.
