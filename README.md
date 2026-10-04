# N’bouyaa Kassinga

Senior AI Engineer with 5+ years of experience taking AI systems from prototype to production. I build RAG and multi-agent platforms, MCP/A2A integrations, and cost-aware LLM serving infrastructure on AWS and Azure.

My focus is practical: reliable systems, measurable business impact, strong observability, and controlled inference costs.

## Featured project

### [LLM Inference Lab](https://github.com/FadelT/llm-inference-lab)

A reproducible lab for understanding and optimizing LLM serving on real GPUs.

- Benchmarked Llama 3.1 8B with vLLM on an NVIDIA L4 hosted on AWS.
- Connected measured latency and throughput to roofline predictions.
- Measured batch scaling from 17 to 803 tokens/s (47× aggregate throughput).
- Tracks TTFT, inter-token latency, GPU utilization, memory bandwidth, and cost.
- Designed for short, reproducible sessions with infrastructure teardown to keep experiments below $1.

Next experiments: FP16/FP8/INT4 quantization, prefix and KV caching, speculative decoding, and profiling.

## Selected production impact

- Built a multi-agent enterprise assistant used by 1,000+ people weekly, combining RAG, document analysis, web search, guardrails, and LLM observability; reduced query-resolution time by 50%.
- Developed an agentic data-migration platform covering approximately 200 pipelines; reduced a five-day migration cycle to around 30 minutes and contributed to roughly €1M in savings.
- Optimized speech-model inference on AWS Inferentia, reducing latency by 10% and infrastructure cost by more than 50%.
- Delivered production systems with Python, FastAPI, LangChain/LangGraph, Amazon Bedrock, Azure, Terraform, Docker, and Kubernetes.

## Open-source contributions

- [BerriAI/litellm#30537](https://github.com/BerriAI/litellm/pull/30537) — added UK PII entity types to the Presidio guardrail integration (merged).
- [strands-agents/harness-sdk#2822](https://github.com/strands-agents/harness-sdk/pull/2822) — build-time validation for Amazon Bedrock `strict_tools` constraints.
- [strands-agents/harness-sdk#2821](https://github.com/strands-agents/harness-sdk/pull/2821) — fixed Anthropic `ParsedTextBlock` serialization warnings.

## Core stack

- **GenAI:** RAG, multi-agent systems, MCP, A2A, tool calling, evaluation, guardrails, Langfuse
- **Inference:** vLLM, model serving, GPU benchmarking, batching, latency/throughput analysis
- **Application:** Python, FastAPI, LangChain, LangGraph, Claude Code skills and workflows
- **Cloud & platform:** AWS Bedrock, AWS Inferentia, Azure, Terraform, Docker, Kubernetes

## Other engineering work

I also maintain quantitative research projects covering systematic strategies, automated experimentation, backtesting, and production monitoring. They are available in my public repositories but remain secondary to my AI engineering work.

## Contact

- [LinkedIn](https://www.linkedin.com/in/n-bouyaa-kassinga-818a02169/)
- [Email](mailto:nbouyaakassinga@gmail.com)
