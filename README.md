# Mastering AI and LLM Engineering 
![image](https://github.com/user-attachments/assets/ba0b3fdc-6b1e-48be-85fb-0820d8d8b8ed)

This repository is a comprehensive resource for learning and mastering the latest and most critical topics in AI and LLM (Large Language Model) Engineering. Below is a detailed table of contents outlining the topics covered in this repository.

## Table of Contents

### 1. Large Language Models (LLMs)
- **LLM Fine-Tuning**
  - [LoRA (Low-Rank Adaptation)](./llm/fine_tuning/lora.md)
  - [PEFT (Parameter-Efficient Fine-Tuning)](./llm/fine_tuning/peft.md)
  - [Prefix Tuning](./llm/fine_tuning/prefix_tuning.md)
- **Prompt Engineering**
  - [Zero-Shot Prompting](./llm/prompt_engineering/zero_shot.md)
  - [Few-Shot Prompting](./llm/prompt_engineering/few_shot.md)
  - [Chain-of-Thought Prompting](./llm/prompt_engineering/chain_of_thought.md)
- **Scaling Laws**
  - [Understanding Model Size and Data Requirements](./llm/scaling_laws/overview.md)
- **LLM Deployment**
  - [Optimized Inference with ONNX](./llm/deployment/onnx.md)
  - [TensorRT](./llm/deployment/tensorrt.md)
  - [Hugging Face Accelerate](./llm/deployment/accelerate.md)
- **Distributed Training**
  - [ZeRO Optimization](./llm/training/zero.md)
  - [Megatron-LM](./llm/training/megatron_lm.md)
  - [DeepSpeed](./llm/training/deepspeed.md)
- **Evaluation**
  - [Perplexity](./llm/evaluation/perplexity.md)
  - [BLEU Score](./llm/evaluation/bleu.md)
  - [ROUGE Score](./llm/evaluation/rouge.md)
  - [BERTScore](./llm/evaluation/bertscore.md)

### 2. Specialized Topics in AI
- **Generative AI**
  - [Text-to-Image: Stable Diffusion, DALL-E](./specialized/generative_ai/text_to_image.md)
  - [Text-to-Audio](./specialized/generative_ai/text_to_audio.md)
  - [Text-to-Video](./specialized/generative_ai/text_to_video.md)
- **Multimodal Models**
  - [CLIP](./specialized/multimodal/clip.md)
  - [Flamingo](./specialized/multimodal/flamingo.md)
  - [UniCLIP](./specialized/multimodal/uniclip.md)
- **Reinforcement Learning**
  - [RLHF (Reinforcement Learning with Human Feedback)](./specialized/reinforcement_learning/rlhf.md)
- **Knowledge Graphs**
  - [Integrating Structured Knowledge into LLMs](./specialized/knowledge_graphs/overview.md)

### 3. MLOps and Engineering Best Practices
- **Model Lifecycle Management**
  - [MLflow](./mlops/lifecycle_management/mlflow.md)
  - [DVC](./mlops/lifecycle_management/dvc.md)
- **Data Engineering**
  - [Apache Airflow](./mlops/data_engineering/airflow.md)
  - [Prefect](./mlops/data_engineering/prefect.md)
- **Model Deployment**
  - [APIs with Flask/FastAPI](./mlops/deployment/apis.md)
  - [Cloud Platforms: AWS Sagemaker, Azure ML, GCP AI Platform](./mlops/deployment/cloud_platforms.md)
  - [Containerization: Docker, Kubernetes](./mlops/deployment/containerization.md)
- **Monitoring**
  - [Drift Detection](./mlops/monitoring/drift_detection.md)
  - [Model Explainability (SHAP, LIME)](./mlops/monitoring/explainability.md)

### 4. Cutting-Edge Research Areas
- **Sparse Models and Efficiency**
  - [Mixture of Experts (MoE)](./research/sparse_models/moe.md)
  - [Distillation](./research/sparse_models/distillation.md)
- **Ethics and Bias in AI**
  - [Responsible AI Principles](./research/ethics/responsible_ai.md)
- **Federated Learning**
  - [Training Models Across Distributed Devices](./research/federated_learning/overview.md)
- **AI Safety and Alignment**
  - [Ensuring LLM Outputs are Aligned with Human Values](./research/safety_alignment/overview.md)

### 5. Tools and Platforms
- **Hugging Face Ecosystem**
  - [Transformers](./tools/hugging_face/transformers.md)
  - [Datasets](./tools/hugging_face/datasets.md)
  - [Accelerate](./tools/hugging_face/accelerate.md)
- **LangChain**
  - [Building Applications with LLMs](./tools/langchain/overview.md)
- **Vector Databases**
  - [Pinecone](./tools/vector_databases/pinecone.md)
  - [Weaviate](./tools/vector_databases/weaviate.md)
  - [TiDB for Retrieval-Augmented Generation (RAG)](./tools/vector_databases/tidb.md)
- **AutoML Frameworks**
  - [AutoGluon](./tools/automl/autogluon.md)
  - [H2O.ai](./tools/automl/h2o.md)

### 6. Mathematics for LLMs
- **Matrix Operations**
  - [Key Concepts for Transformers](./mathematics/matrix_operations.md)
- **Probability Distributions**
  - [Essential for LLM Outputs](./mathematics/probability_distributions.md)
- **Information Theory**
  - [Cross-Entropy Loss, KL Divergence](./mathematics/information_theory.md)
- **Graph Theory**
  - [Applications in Knowledge Graphs and GNNs](./mathematics/graph_theory.md)

---

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the repository.

## License
This repository is licensed under the MIT License. See [LICENSE](./LICENSE) for details.
