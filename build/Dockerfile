FROM quay.io/operator-framework/helm-operator:v0.12.0

### Required OpenShift Labels
LABEL name="NeuVector Operator" \
      vendor="NeuVector" \
      version="v0.0.1" \
      release="1" \
      summary="NeuVector container security solution." \
      description="The Allinone container provides everything needed to evaluate NeuVector on a single host. Please contact support@neuvector.com to request a free-trial license key."

# Required Licenses
COPY licenses /licenses


COPY watches.yaml ${HOME}/watches.yaml
COPY helm-charts/ ${HOME}/helm-charts/
