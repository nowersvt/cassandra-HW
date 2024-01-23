# Cassandra-HW

> *Dependency*

* Docker
* Kubernetes
* Helm
* Make

---

> How To Deploy & Check

```apache
git clone https://github.com/nowersvt/cassandra-HW.git
cd cassandra-HW/
make deploy-cassandra
```

check work nodes `kubectl get nodes`

check running all pods `kubectl get po -A `

check describe pods `kubectl describe pods `
