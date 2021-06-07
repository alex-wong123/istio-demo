# istio-demo onlineboutique
This demo is from Google microservice demo.
The git repository url as follow:
https://github.com/GoogleCloudPlatform/microservices-demo

|-- online-boutique
|   |-- cluster1      ###micro services deployed on cluster1
|   |   |-- cartservice.yaml
|   |   |-- frontend.yaml
|   |   |-- productcatalogservice.yaml
|   |   |-- recommendationservice.yaml
|   |   |-- redis-cart.yaml
|   |   `-- shippingservice.yaml
|   |-- cluster1-services.yaml    ### k8s services which related micro services deployed on cluster2 also should be deploy on cluster1
|   |-- cluster2    ###micro services deployed on cluster2
|   |   |-- adservice.yaml
|   |   |-- checkoutservice.yaml
|   |   |-- currencyservice.yaml
|   |   |-- emailservice.yaml
|   |   |-- loadgenerator.yaml
|   |   `-- paymentservice.yaml
|   |-- cluster2-istio-gw.yaml    ### istio gateway and virtualservice deployed on cluster2
|   `-- cluster2-services.yaml    ### k8s services which related micro services deployed on cluster1 also should be deploy on cluster2
`-- README.md
