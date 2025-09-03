# Kubernetes Labs

Hands-on Kubernetes labs designed to build foundational skills and mentorship support for aspiring contributors and learners.

---

## 🚀 Overview

This repository offers a progressive series of Kubernetes labs, starting from basic Pods and working up to advanced concepts like Services, Ingress, ConfigMaps, Secrets, and Resource Management. Each lab is structured to reinforce learning through hands-on experience.

---

## 📂 Repository Structure

kubernetes-labs/
├── 01-basic-pod/ # Simple Pod deployment with README
├── 02-deployment-service/ # Deployment + Service example
├── 03-ingress/ # Ingress configuration
├── 04-configmap-secret/ # ConfigMap & Secret use cases
├── 05-resource-limits/ # Pod resource constraints demo
├── 06-deployments-scaling/ # Deployment scaling workshop
├── student-labs/ # Simplified lab versions for learners
├── manifests/ # (Optional) All JSON/YAML in one place
├── images/ # Screenshots and visuals
├── README.md # This overview
└── MENTORSHIP.md # Guidance for mentors and learners



---

## 🛠️ How to Use This Repo

1. **Clone the repo**:

```bash
git clone https://github.com/Wiryenkfea-Eric/kubernetes-labs.git
cd kubernetes-labs
```



**For each lab**:

1. Open the folder (e.g., 01-basic-pod/)

2. Read README.md for lab details, YAML commands, and expected outcomes

3. Run the kubectl commands to experiment and visualize results

4. Use images/ for screenshots or logs of your success per lab


## 📚 Labs Overview

- **Lab 01 – Basic Pod**  
  Deploy a Pod and practice port-forwarding.

- **Lab 02 – Deployment & Service**  
  Launch a Deployment, expose it with a Service.

- **Lab 03 – Ingress**  
  Use Ingress to route traffic to multiple apps.

- **Lab 04 – ConfigMap & Secret**  
  Externalize configuration and secure credentials.

- **Lab 05 – Resource Limits**  
  Apply resource requests and limits on Pods.

- **Lab 06 – Deployments & Scaling**  
  Scale Deployments and monitor pod distribution.


---

## 🎓 Learning & Mentorship Flow

Check out [MENTORSHIP.md](./MENTORSHIP.md) for:

- Learning outcomes  
- Suggested student progression  
- Assessment criteria and submission format  

---

## 💡 Getting Started Tips

- Preview YAML files and docs before running them  
- Use Minikube or a Kubernetes cluster locally  
- Validate deployments with:  

```
bash
kubectl get pods,svc,ingress -n demo
```

## 📖 Resources

- [Kubernetes Documentation](https://kubernetes.io/docs/home/)
- [Minikube Guide](https://minikube.sigs.k8s.io/docs/start/)
- [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

