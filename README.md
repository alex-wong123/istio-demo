# istio-demo onlineboutique
This demo is from Google microservice demo.<br>
It was split to deploy on two k8s clusters. <br>
The git repository url as follow:<br>
https://github.com/GoogleCloudPlatform/microservices-demo

>|-- online-boutique <br>
>|   |-- cluster1      \#micro services deployed on cluster1 <br>
>|   |   |-- cartservice.yaml <br>
>|   |   |-- frontend.yaml <br>
>|   |   |-- productcatalogservice.yaml <br>
>|   |   |-- recommendationservice.yaml <br>
>|   |   |-- redis-cart.yaml <br>
>|   |   \`-- shippingservice.yaml <br>
>|   |-- cluster1-services.yaml    \#k8s services which related micro services deployed on cluster2 also should be deployed on cluster1 <br>
>|   |-- cluster2    \#micro services deployed on cluster2 <br>
>|   |   |-- adservice.yaml <br>
>|   |   |-- checkoutservice.yaml <br>
>|   |   |-- currencyservice.yaml <br>
>|   |   |-- emailservice.yaml <br>
>|   |   |-- loadgenerator.yaml <br>
>|   |   -- paymentservice.yaml <br>
>|   |-- cluster2-istio-gw.yaml    \#istio gateway and virtualservice deployed on cluster2 <br>
>|   -- cluster2-services.yaml    \#k8s services which related micro services deployed on cluster1 also should be deployed on cluster2 <br>
>\`-- README.md <br>
