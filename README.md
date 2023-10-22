# Sample App

A helm chart to deploy a sample application to smoke test Kubernetes functionality


# Using this chart

```
# Install 
helm \
  upgrade \
  --install \
  --create-namespace \
  --namespace sample-app \
  --values values.yaml \
  sample-app \
  ./

# Uninstall
helm \
  uninstall \
  --namespace sample-app \
  sample-app
 ```

