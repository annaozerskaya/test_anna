# test_anna
Key  | Type | Required  | Description | Default
------------- | ------------- | ------------- | ------------- | -------------
metadata | map  | true | Standard ingress's metadata.  | none 
spec  | map  | true  |  Defines the behavior of a ingress.  | none
spec.backend | map | false | Defines the referenced service endpoint to which the traffic will be forwarded to.| none 
spec.rule  | map  | false  | A list of host rules used to configure the Ingress.  | If unspecified, or no rule matches, all traffic is sent to the default backend   
spec.rule.http  | map  | true  | is a list of http selectors pointing to backends. | none
http.path.backend  | map  | true  | Defines the referenced service endpoint to which the traffic will be forwarded to.  | none
http.path.path  | string  | true  | String or an extended POSIX regular expression as defined by matched against the path of an incoming request.  | sending traffic to the backend
spec.tls  | map  | false  | Currently the Ingress only supports a single TLS port, 443.  | none
