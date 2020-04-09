# GNCR portal
Static website and sample code/config for deploying R code like Shiny to the IBM cloud with app id.

* `shiny-loadbalancer` - simple Shiny app ("myshiny") built with Docker and deployed with Kubernetes using a LoadBalancer service.
* `ingress` - composite app using the "myshiny" app from the previous example, adding a web app with a static page, deploying these two on Kubernetes with Ingress, with URL Rewrite and integration with App ID for authentication.
