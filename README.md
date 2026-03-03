# Aria: An Open Multimodal Native MoE Mixture-of-Experts Model

Aria is an open multimodal native mixture-of-experts (MoE) model developed by Rhymes AI. It is designed to handle both visual and textual inputs effectively, making it suitable for a wide range of multimodal tasks.

## Features

- **Multimodal Native**: Designed from the ground up to process both images and text
- **Mixture of Experts**: Uses MoE architecture for efficient scaling
- **Long Context Support**: Supports up to 64K tokens context length
- **Video Understanding**: Capable of processing and understanding video content
- **Fine-tuning Support**: Includes recipes for both full fine-tuning and LoRA

## Installation

```bash
pip install -e .
```

## Quick Start

```python
from aria.model import AriaForConditionalGeneration
from transformers import AutoTokenizer

model = AriaForConditionalGeneration.from_pretrained("rhymes-ai/Aria")
tokenizer = AutoTokenizer.from_pretrained("rhymes-ai/Aria")
```

## Documentation

For more details, please refer to the [documentation](docs/).

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

---

## Related Projects

1. related project [Qwen2.5-VL](https://github.com/QwenLM/Qwen2.5-VL)
2. related project [DeepSeek-VL2](https://github.com/deepseek-ai/DeepSeek-VL2)
