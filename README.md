# Interactive Kubernetes Learning Path

This project provides an interactive, web-based learning path to understand core Kubernetes concepts. It's designed to give a high-level, visual overview of different components and how they relate to each other.

## Learning Modules

The learning path currently includes the following modules:

1.  **Core Concepts**: Understand the fundamentals like Pods, Deployments, and ReplicaSets.
2.  **Service Types**: Learn how services like ClusterIP, NodePort, and LoadBalancer expose your applications.
3.  **Ingress**: Discover how to manage external access to the services in a cluster.
4.  **Config & Secrets**: Manage application configuration and secrets securely.
5.  **Persistent Storage**: Explore how to handle stateful applications with Persistent Volumes (PV) and Persistent Volume Claims (PVC).

Each module will eventually link to a dedicated visualizer page.

## Getting Started

To run this project locally, you need a simple web server.

1.  Clone the repository:
    ```bash
    git clone git@github.com:vanjara/kubernetes-visualizer.git
    cd kubernetes-visualizer
    ```

2.  If you have Python 3 installed, you can run a simple web server:
    ```bash
    python3 -m http.server
    ```
    If you have Python 2:
    ```bash
    python -m SimpleHTTPServer
    ```

3.  Open your web browser and navigate to `http://localhost:8000`.

## Technology Stack

*   **HTML/CSS/JavaScript**: The core of the web interface.
*   **Tailwind CSS**: For utility-first styling.
*   **D3.js**: For creating the interactive data-driven visualizations.

## Contributing

Contributions are welcome! If you have ideas for new visualizations, improvements, or bug fixes, please open an issue or submit a pull request. 