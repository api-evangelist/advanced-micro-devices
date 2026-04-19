# Advanced Micro Devices (advanced-micro-devices)
Advanced Micro Devices (AMD) is a global semiconductor company that develops high-performance computing, graphics, and visualization technologies for data centers, gaming, and embedded markets. AMD provides the ROCm open software platform for GPU computing, HIP programming interface, and the AMD Developer Cloud for AI workloads using AMD Instinct GPUs.

**URL:** [Visit Advanced Micro Devices](https://developer.amd.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, Cloud Computing, GPU, HPC, Machine Learning, Semiconductor

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### AMD Developer Cloud API
The AMD Developer Cloud API provides access to AMD Instinct GPU instances for AI inference, training, and HPC workloads. Supports managing compute instances, deploying AI models, monitoring GPU utilization, and integrating with ROCm-compatible frameworks including PyTorch, TensorFlow, and vLLM.

**Human URL:** [https://developer.amd.com](https://developer.amd.com)

#### Tags:

 - AI, Cloud Computing, GPU, HPC, Instinct

#### Properties

- [Documentation](https://developer.amd.com)
- [OpenAPI](openapi/amd-developer-cloud-api-openapi.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/amd-developer-cloud-api-context.jsonld)
- [SpectralRules](rules/amd-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/developer-cloud-api.yaml)
- [Vocabulary](vocabulary/advanced-micro-devices-vocabulary.yaml)

### AMD ROCm API
The AMD ROCm (Radeon Open Compute) platform provides the runtime and library APIs for GPU-accelerated computing on AMD hardware. Includes HIP (Heterogeneous-compute Interface for Portability), math libraries (rocBLAS, rocFFT, rocRAND), and communication libraries (RCCL) for high-performance computing and AI workloads.

**Human URL:** [https://rocm.docs.amd.com](https://rocm.docs.amd.com)

#### Tags:

 - GPU, HPC, Machine Learning, ROCm, SDK

#### Properties

- [Documentation](https://rocm.docs.amd.com)
- [OpenAPI](openapi/amd-rocm-management-api-openapi.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/amd-rocm-management-api-context.jsonld)
- [SpectralRules](rules/amd-spectral-rules.yml)
- [NaftikoCapability](capabilities/ai-gpu-computing.yaml)
- [Vocabulary](vocabulary/advanced-micro-devices-vocabulary.yaml)

## Common Properties

- [Website](https://www.amd.com)
- [Portal](https://developer.amd.com)
- [Documentation](https://rocm.docs.amd.com)
- [GettingStarted](https://developer.amd.com/resources/rocm-resources/)
- [Support](https://developer.amd.com/support/)
- [Blog](https://www.amd.com/en/corporate/blog.html)
- [TermsOfService](https://www.amd.com/en/legal/terms-and-conditions.html)
- [PrivacyPolicy](https://www.amd.com/en/legal/privacy.html)
- [GitHubOrganization](https://github.com/ROCm)
- [Academy](https://academy.amd.com)
- [SignUp](https://developer.amd.com/amd-developer-cloud/)

## Features

| Name | Description |
|------|-------------|
| AMD Instinct GPU Instances | On-demand access to MI300X, MI250, and MI210 GPU instances for AI training, inference, and HPC workloads. |
| ROCm Software Platform | Open-source GPU compute platform with HIP programming model, math libraries, and deep learning framework support. |
| HIP Programming Interface | CUDA-compatible GPU programming interface enabling portable code across AMD and NVIDIA hardware. |
| AI Model Serving | Deploy and serve large language models using vLLM, TGI, and other inference engines on AMD Instinct GPUs. |
| ROCm Math Libraries | Optimized libraries including rocBLAS, rocFFT, rocRAND, and rocSPARSE for scientific computing and deep learning. |
| Multi-GPU Communication | RCCL (ROCm Communication Collectives Library) for efficient multi-GPU and multi-node collective operations. |
| AI Developer Cloud Credits | Free GPU cloud credits for qualifying researchers, startups, and developers through the AMD AI Developer Program. |
| Framework Compatibility | Full compatibility with PyTorch, TensorFlow, JAX, and other ML frameworks via ROCm backend support. |

## Use Cases

| Name | Description |
|------|-------------|
| Large Language Model Training | Train and fine-tune large language models on AMD Instinct GPU clusters with ROCm-optimized PyTorch. |
| AI Inference Serving | Deploy LLM inference endpoints using vLLM on AMD Instinct GPUs for high-throughput token generation. |
| Scientific Computing | Run HPC simulations, molecular dynamics, and fluid dynamics workloads on AMD GPU clusters with ROCm. |
| Computer Vision | Train and deploy image classification, object detection, and segmentation models using AMD GPU acceleration. |
| Data Analytics | Accelerate data processing and analytics workloads using GPU-accelerated computing with ROCm. |
| Generative AI Development | Develop and iterate on generative AI applications using AMD Developer Cloud free GPU credits. |

## Integrations

| Name | Description |
|------|-------------|
| PyTorch | Full ROCm support for PyTorch including autograd, distributed training, and all major model architectures. |
| TensorFlow | TensorFlow-ROCm integration enabling GPU-accelerated training and inference on AMD hardware. |
| vLLM | AMD Instinct Day-0 support in vLLM for high-performance LLM inference serving. |
| Hugging Face | Transformers and Diffusers library compatibility with ROCm for loading and running models from Hugging Face Hub. |
| Kubernetes | AMD GPU operator for Kubernetes enabling GPU-accelerated containerized workloads on AMD hardware. |
| Docker | Official ROCm Docker images for containerized GPU computing environments. |
| ONNX Runtime | ONNX Runtime ROCm execution provider for cross-framework model deployment on AMD GPUs. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AMD Developer Cloud API](openapi/amd-developer-cloud-api-openapi.yml)
- [AMD ROCm Management API](openapi/amd-rocm-management-api-openapi.yml)

### JSON Schema

- 14 schema files in [json-schema/](json-schema/)

### JSON Structure

- 14 structure files in [json-structure/](json-structure/)

### JSON-LD

- [AMD Developer Cloud API Context](json-ld/amd-developer-cloud-api-context.jsonld)
- [AMD ROCm Management API Context](json-ld/amd-rocm-management-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AMD Developer Cloud API](capabilities/shared/developer-cloud-api.yaml) — 7 operations for GPU instance management, AI model deployment, metrics, and billing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [AI GPU Computing](capabilities/ai-gpu-computing.yaml) | AMD Developer Cloud API | 8 | AI Researchers, ML Engineers, HPC Developers |

## Vocabulary

- [Advanced Micro Devices Vocabulary](vocabulary/advanced-micro-devices-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [AMD Spectral Rules](rules/amd-spectral-rules.yml) — 30 rules across 11 categories enforcing AMD API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
