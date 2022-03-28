# Integrating simple nginx app with TSM 

By default the nginx example deploys a service via a load balancer.  If TSM is deployed and the namespace istioenabled then the app will get an envoy proxy sidecar which will prevent the direct access.  This gateway.yaml does a very simple mapping from the TSM ingress gateway to the nginx yaml file so that the application can be reached via TSM.
