
# Get the PodIP of a given pod
curl http://$(kubectl get pod PODID -o=template -t={{.status.podIP}})
