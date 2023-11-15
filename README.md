# keda-workshop

autoscaling.keda.sh/paused: "true"

kubectl -n nginx annotate -l scaler.keda=true so autoscaling.keda.sh/paused-replicas=0
kubectl -n nginx annotate -l scaler.keda=true so autoscaling.keda.sh/paused=true

kubectl -n nginx job1 -l scaler.keda=true sj autoscaling.keda.sh/paused=true

kubectl -n nginx annotate -l scaler.keda=true so autoscaling.keda.sh/paused-replicas-
kubectl -n nginx annotate -l scaler.keda=true so autoscaling.keda.sh/paused-

kubectl -n nginx job1 -l scaler.keda=true sj autoscaling.keda.sh/paused-
