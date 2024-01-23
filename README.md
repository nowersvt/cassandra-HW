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
Check the working database: `make testConnect-to-db `

Connect to the application client pod: `make connect-app-client`

Connect to the Cassandra database console: `make connect-cassandra-db `

Verify the status of Kubernetes nodes: `kubectl get nodes`

List all running pods : `kubectl get po -A `

Describe all pods in detail: `kubectl describe pods `
