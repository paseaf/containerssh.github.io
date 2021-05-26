title: Backend selection

{{ reference_outdated() }}

ContainerSSH is built to support multiple backends. The backend can be changed in the configuration file:

```yaml
backend: <backend type>
```

ContainerSSH currently supports the following backends:

| Backend | Description |
|---------|-------------|
| [`docker`](docker.md) | Runs Docker containers. |
| [`kubernetes`](kubernetes.md) | Runs Kubernetes containers. |
| [`sshproxy`](sshproxy.md) | Forwards SSH connections to a backend server. |
| [`dockerrun`](dockerrun.md) | Deprecated backend that runs Docker containers. |
| [`kuberrun`](kuberun.md) | Deprecated backend that runs Kubernetes pods. |