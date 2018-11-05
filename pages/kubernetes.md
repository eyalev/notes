
# Kubernetes

## Workflows

### Dashboard in the terminal

- I create a dashboard in a `tmux` window with multiple `panes`
- Each pane has a `kubectl` prefixed with a `watch` command.
  - Examples
    - `watch -d kubectl get pods -a`
    - `watch -d kubectl get jobs`

## Maximum Nodes in Cluster

`5000`

- Updated: 2018-10-21
- Source: https://kubernetes.io/docs/setup/cluster-large/
 
## One liner interactive shell in a pod deployment

Example: `kubectl run -i --tty busybox --image=busybox -- sh`

https://kubernetes.io/docs/reference/kubectl/cheatsheet/

## Services do not ping
- https://github.com/kubernetes/kubernetes/issues/7996#issuecomment-299497122
  - > Services do not ping.
    - @thockin
- https://stackoverflow.com/questions/50852542/kubernetes-cannot-ping-another-service
  - > Ping doesn't work with service's cluster IPs like 10.233.14.157, as it is a virtual IP. You should be able to ping a specific pod, but no a service.

## Sidecar container pattern

- https://kubernetes.io/docs/concepts/workloads/pods/pod-overview/
  - https://kubernetes.io/blog/2015/06/the-distributed-system-toolkit-patterns/#example-1-sidecar-containers
  - https://kubernetes.io/blog/2016/06/container-design-patterns/
    - https://www.usenix.org/conference/hotcloud16/workshop-program/presentation/burns
      - https://www.usenix.org/system/files/conference/hotcloud16/hotcloud16_burns.pdf
      - https://www.usenix.org/sites/default/files/conference/protected-files/hotcloud16_slides_burns.pdf

