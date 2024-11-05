# k8s-opa-gatekeeper-demo

This project is demoing OPA Gatekeeper with Kubernetes. Gatekeeper is an opensource project supported by CNCF. It aims for creating policies to manage Kubernetes like:

* Enforcing labels on namespaces.
* Allowing only images coming from certain Docker Registries.
* Require all Pods specify resource requests and limits.
* Prevent conflicting Ingress objects from being created.
* Enforcing running containers as non-root.
