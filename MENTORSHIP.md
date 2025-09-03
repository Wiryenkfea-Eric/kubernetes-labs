# Mentorship Guide for Kubernetes Labs

## Introduction
This mentorship program is designed to guide students step by step through the fundamentals of Kubernetes.  
By combining hands-on labs with mentorship-driven learning, students gain both **practical skills** and **conceptual clarity**, ensuring they can confidently work with Kubernetes in real-world scenarios.

---

## Learning Outcomes
By completing these labs, students will be able to:

- Understand the fundamentals of Kubernetes objects (Pods, Deployments, Services, Ingress).
- Apply declarative YAML manifests to manage Kubernetes workloads.
- Demonstrate scaling and resource management for applications.
- Implement configuration and secret management securely.
- Troubleshoot common Kubernetes issues effectively.

---

## Suggested Flow for Students

- [Lab 01 - Basic Pod](01-basic-pod/README.md)  
  Learn how to create a Pod and expose it locally.

- [Lab 02 - Deployment & Service](02-deployment-service/README.md)  
  Explore replicas, rolling updates, and Service exposure.

- [Lab 03 - Ingress](03-ingress/README.md)  
  Route traffic between multiple applications.

- [Lab 04 - ConfigMaps & Secrets](04-configmap-secret/README.md)  
  Manage externalized configuration and sensitive data.

- [Lab 05 - Resource Limits](05-resource-limits/README.md)  
  Apply CPU/memory constraints and test resource usage.

- [Lab 06 - Deployments & Scaling](06-deployments-scaling/README.md)  
  Scale applications and verify load distribution.

---

## Assessment Criteria
✅ Student can successfully deploy and scale Pods.  
✅ Student explains the purpose of Services vs Ingress.  
✅ Student demonstrates secure usage of ConfigMaps and Secrets.  
✅ Student monitors Pods and resolves basic troubleshooting issues.  
✅ Student presents submissions as proof of completion.  

**Submission Format:**  
- Create a `labXX-submission.md` file (e.g., `lab01-submission.md`).  
- Include command outputs, screenshots, and explanations.  

---

## Mentorship Tips
- Ask questions early if stuck — don’t struggle in silence.  
- Pair with peers to review YAML manifests and troubleshoot together.  
- Focus on *why* a configuration works, not just copy-pasting.  
- Share your progress with mentors regularly for feedback.  

---

## Next Steps After Labs
Once students complete these foundational labs, they are encouraged to explore:  
- **Helm** – Package management for Kubernetes.  
- **Kubernetes Operators** – Extending Kubernetes with custom controllers.  
- **CI/CD Integration** – Automating deployments with pipelines (e.g., GitHub Actions, ArgoCD, Jenkins).  
- **Monitoring & Logging** – Tools like Prometheus, Grafana, and ELK stack.  

---

This guide is designed to support hands-on, mentorship-driven learning across different experience levels.
