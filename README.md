# kubectl-otel-trace
Trace kubectl commands using OpenTelemetry.

```
kubectl oteltrace <Your Existing Command>
```

For example:

```
kubectl oteltrace apply -f deployment.yaml
```

This can be aliased to make it more automated:

```
alias ko='kubectl oteltrace'
ko apply -f deployment.yaml
```
