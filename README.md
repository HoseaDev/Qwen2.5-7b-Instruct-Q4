# Qwen2.5-7B-Instruct (Q4_K_M 量化版)

这是阿里云通义千问 Qwen2.5-7B-Instruct 模型的 4 位量化版本，使用 llama.cpp 的 Q4_K_M 量化方法。

## 模型信息

- **原始模型**: [Qwen/Qwen2.5-7B-Instruct](https://huggingface.co/Qwen/Qwen2.5-7B-Instruct)
- **量化方法**: Q4_K_M (4-bit)
- **文件大小**: 约 4GB (原始模型约 14GB)
- **适用场景**: 本地部署、资源受限环境

## 使用方法

```bash
ollama pull HoseaDev/Qwen2.5-7b-Instruct-Q4
ollama run HoseaDev/Qwen2.5-7b-Instruct-Q4
