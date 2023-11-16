# keda-workshop

autoscaling.keda.sh/paused: "true"

### SO

kubectl -n nginx annotate -l scaler.keda=true so autoscaling.keda.sh/paused-replicas=0
kubectl -n nginx annotate -l scaler.keda=true so autoscaling.keda.sh/paused=true

kubectl -n nginx annotate -l scaler.keda=true so autoscaling.keda.sh/paused-replicas-
kubectl -n nginx annotate -l scaler.keda=true so autoscaling.keda.sh/paused-

### SJ

kubectl -n job1 annotate -l scaler.keda=true sj autoscaling.keda.sh/paused=true
kubectl -n job1 annotate -l scaler.keda=true sj autoscaling.keda.sh/paused-
