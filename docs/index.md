---
hide:
  - navigation
  - toc
---

[NeMo-Skills](https://github.com/NVIDIA/NeMo-Skills) is a collection of pipelines to improve "skills" of large language models. You can use it to generate synthetic data, train/evaluate models, analyzing outputs and more!
Here are some of the things we support.

- [Flexible inference](basics/inference.md): Seamlessly switch between API providers, local server and large-scale slurm jobs for LLM inference.
- [Multiple formats](pipelines/checkpoint-conversion.md): Use any of the [NeMo](https://github.com/NVIDIA/NeMo), [vLLM](https://github.com/vllm-project/vllm), [sglang](https://github.com/sgl-project/sglang)
  and [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) servers and easily convert checkpoints from one format to another.
- [Model evaluation](pipelines/evaluation.md): Evaluate your models on many popular benchmarks
    - Math problem solving: hmmt_feb25, brumo25, aime24, aime25, omni-math (and many more)
    - Formal proofs in Lean: minif2f, proofnet
    - Coding skills: scicode, livecodebench, human-eval, mbpp
    - Chat/instruction following: ifeval, arena-hard, mt-bench
    - General knowledge: mmlu, mmlu-pro, gpqa
    - Long context: ruler
- [Model training](pipelines/training.md): Train models at speed-of-light using [NeMo-Aligner](https://github.com/NVIDIA/NeMo-Aligner/), [NeMo-RL](https://github.com/NVIDIA/NeMo-RL/) or [verl](https://github.com/volcengine/verl).


To get started, follow these [steps](basics/index.md), browse available [pipelines](./pipelines/index.md) or run `ns --help` to see all available
commands and their options.

You can find more examples of how to use NeMo-Skills in the [tutorials](./tutorials/index.md) page.
