# kournalctl

Mount the node filesystem system journal as read only and use `journalctl` in Kubernetes.

## Installing

```bash
git clone git@github.com:kris-nova/kournalctl.git
cd kournalctl
source kournalctl.source
kournalctl -fu kubelet
kournalctl -f
kournalctl -fu falco
```

Have fun kiddos.
