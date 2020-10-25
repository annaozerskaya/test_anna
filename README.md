# test_anna
Key  | Type | Required  | Description | Default
------------- | ------------- | ------------- | ------------- | -------------
metadata | map  | true | Standard ingress's metadata.  | none 
spec  | map  | true  |  Defines the behavior of a ingress.  | none
spec.backend | map | false | Defines the referenced service endpoint to which the traffic will be forwarded to.| none 
spec.rule  | map  | false  | A list of host rules used to configure the Ingress. If unspecified, or no rule matches, all traffic is sent to the default backend.  | none   
spec.rule.http  | 

