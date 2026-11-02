## Derek Prescott

**MLOps Infrastructure Architect**

### System Design: ML Platform v2

**Components Built:**
```
User Submission → Data Validation → Feature Engineering
    ↓
Model Registry ← Training Pipeline ← Hyperparameter Optimization
    ↓
A/B Testing Framework → Model Serving (Kubernetes)
    ↓
Monitoring & Alerting → Retraining Triggers
```

**Scale Metrics:**
- 50+ concurrent model instances
- GPU cluster orchestration (200+ GPUs)
- Real-time inference SLA: p99 < 100ms
- Automated model deployment every 6 hours
- Data pipeline: 2TB daily processing

**Recent Work:** Implementing auto-scaling based on model inference demand and data drift detection to trigger retraining before performance degrades.