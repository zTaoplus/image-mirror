# Image Mirror

There exists images that are difficult to pull in some countries, such as images on ghcr or gcr. This project is to mirror those images to docker hub that is more accessible in such countries.

## Mirrored Images

Source Image | Mirrored Image | Latest Tag | Status | Original Repo
--- | --- | --- | --- | ---
gcr.io/arrikto/kubeflow/oidc-authservice | zjuici/mirror.arrikto.oidc-authservice | 0c4ea9a | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/oidc-authservice.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/oidc-authservice.yml) | <https://github.com/arrikto/oidc-authservice/>
gcr.io/knative-releases/knative.dev/serving/cmd/activator | zjuici/mirror.knative-serving.serving-core.activator | v1.11.0 | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-activator.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-activator.yml) | <https://github.com/knative/serving/>
gcr.io/knative-releases/knative.dev/serving/cmd/autoscaler | zjuici/mirror.knative-serving.serving-core.autoscaler | v1.11.0 | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-autoscaler.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-autoscaler.yml) | <https://github.com/knative/serving/>
gcr.io/knative-releases/knative.dev/serving/cmd/controller | zjuici/mirror.knative-serving.serving-core.controller | v1.11.0 | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-controller.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-controller.yml) | <https://github.com/knative/serving/>
gcr.io/knative-releases/knative.dev/serving/cmd/webhook | zjuici/mirror.knative-serving.serving-core.webhook | v1.11.0 | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-webhook.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-webhook.yml) | <https://github.com/knative/serving/>
gcr.io/knative-releases/knative.dev/serving/cmd/queue | zjuici/mirror.knative-serving.serving-core.queue | v1.11.0 | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-queue.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-queue.yml) | <https://github.com/knative/serving/>
gcr.io/knative-releases/knative.dev/net-istio/cmd/controller | zjuici/mirror.knative-serving.net-istio.controller | v1.11.0 | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-net-istio-controller.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-net-istio-controller.yml) | <https://github.com/knative-extensions/net-istio/>
gcr.io/knative-releases/knative.dev/net-istio/cmd/webhook | zjuici/mirror.knative-serving.net-istio.webhook | v1.11.0 | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-net-istio-webhook.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/knative-serving-net-istio-webhook.yml) | <https://github.com/knative-extensions/net-istio/>
ghcr.io/huggingface/text-generation-inference | -- | -- | [![CI](https://github.com/ZJUICI/image-mirror/actions/workflows/tgi.yml/badge.svg)](https://github.com/ZJUICI/image-mirror/actions/workflows/tgi.yml) | <https://github.com/huggingface/text-generation-inference/>
