~# Tech Context

## Technologies Used
*   Go
*   Kubernetes API
*   NVIDIA GPU Driver
*   Helm (for deployment)

## Development Setup
*   Go development environment
*   Kubernetes cluster (e.g., Minikube, Kind, GKE)
*   NVIDIA GPU-enabled nodes

## Technical Constraints
*   Requires a Kubernetes cluster with NVIDIA GPUs.
*   Dependencies on specific versions of the NVIDIA GPU driver and Kubernetes API.

## Dependencies
*   k8s.io/api
*   k8s.io/apimachinery
*   k8s.io/client-go
*   github.com/NVIDIA/go-nvlib
