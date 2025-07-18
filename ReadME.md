# Navigate to chart directory
cd my-nginx-chart

# Install the chart
helm install my-nginx ./ --namespace test --create-namespace

# Check resources
kubectl get all -n test
