# How to install this selenium grid?

1. cd selenium-grid/
2. create new namespace `kubectl create ns selenium`
3. use helm and run `helm install -f values.yaml selenium . -n selenium`

# How to test your selenium grid?
run `kubectl port-forward svc/selenium-grid -n selenium 4444:4444`