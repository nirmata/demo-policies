# Kyverno Policies

This repository contains a set of Kyverno policies curated and managed by the Nirmata team for use as policy groups within [Nirmata Enterprise for Kyverno](https://nirmata.com/kyverno-enterprise/), and [Nirmata Control Hub](https://nirmata.com/nirmata-control-hub/).

For more information, visit our website at [https://nirmata.com/](https://nirmata.com/).

Sign-up for a free trial today at [https://try.nirmata.io/](https://try.nirmata.io/)


## Installing Policies

**Clone Repository:**

Clone the kyverno-policies repository.

```console
git clone https://github.com/nirmata/demo-policies.git
```


**Install Policies:**


```console
cd demo-policies
kubectl apply -f <policy-dir>
```

Once policies are installed, you can check if they are ready using the command:

```console
kubectl get cpol
```
