# kubernetes-dashboard

[kubernetes/dashboard](https://github.com/kubernetes/dashboard) with authentication / authorization disabled.

## Usage

```sh
git clone https://github.com/isaryo13/kubernetes-dashboard.git
kubectl apply -k ./kubernetes-dashboard
kubectl proxy
```

Now access Dashboard at:

[`http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/`](http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/).
