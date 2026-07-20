```bash
kubectl delete secret plex-claim
kubectl create secret generic plex-claim --from-literal=PLEX_CLAIM=XXXX
```