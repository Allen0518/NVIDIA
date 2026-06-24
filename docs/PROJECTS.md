# Portfolio Projects

## 1. Vision GPU Inference Service

**Window:** W30–W34  
**Purpose:** demonstrate an end-to-end GPU vision serving stack.

### Scope
- OpenCV preprocessing
- PyTorch → ONNX → TensorRT
- Triton Inference Server
- HTTP/gRPC client or API wrapper
- Dynamic batching and metrics
- Latency, throughput, GPU utilization benchmark

### Definition of done
- [ ] Reproducible Docker setup
- [ ] Architecture diagram
- [ ] Benchmark report with p50/p95 latency and throughput
- [ ] README with run steps
- [ ] Demo video or GIF
- [ ] Failure cases documented

## 2. Multimodal Visual AI Service

**Window:** W35–W36  
**Purpose:** combine visual input and language output with structured JSON and human review.

### Scope
- Visual inspection / event analysis use case
- VLM or multimodal serving endpoint
- Structured output schema
- Human-review feedback capture
- Evaluation examples and failure analysis

### Definition of done
- [ ] Working image-to-JSON workflow
- [ ] Prompt/output schema documented
- [ ] Example evaluation set
- [ ] Demo and architecture diagram

## 3. AWS GPU Inference Platform

**Window:** W37–W39  
**Purpose:** demonstrate cloud-native AI infrastructure competence.

### Scope
- GPU nodes and Kubernetes scheduling
- GPU Operator / DCGM metrics concepts
- Triton deployment
- Model artifact storage
- IAM, networking, monitoring, cost, and scaling design

### Definition of done
- [ ] Infrastructure diagram
- [ ] Kubernetes manifests or IaC skeleton
- [ ] Observability design
- [ ] Cost and autoscaling decision note
- [ ] Deployment runbook

## 4. Simulation-to-Edge Vision AI Platform

**Window:** W43–W49  
**Purpose:** demonstrate Physical AI system thinking from simulation to deployment.

### Scope
- OpenUSD / Omniverse scene
- Isaac Sim sensors and synthetic data
- Vision model evaluation
- ONNX / TensorRT inference
- ROS 2 data or sensor pipeline
- Edge deployment constraints: latency, power, memory, thermal, connectivity, fallback

### Definition of done
- [ ] USD scene / simulation evidence
- [ ] Synthetic dataset or sensor recording
- [ ] Model evaluation and benchmark
- [ ] ROS 2 integration or equivalent message-flow demo
- [ ] Edge deployment design
- [ ] Final demo, architecture, README, resume bullets

## Evidence checklist for every project

- [ ] Source code / notebook
- [ ] Architecture diagram
- [ ] Benchmark or evaluation report
- [ ] README and reproducibility instructions
- [ ] Demo artifact
- [ ] Reflection: trade-offs, failure modes, next iteration
