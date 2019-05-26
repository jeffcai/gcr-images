# gcr-images
proxy for pulling images on gcr


## tekton

kubectl apply -f ./tecktoncd/release-0.3.1.yaml

- registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-controller:0.3.1
- registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-webhook:0.3.1
- tekton-pipelines-bash: registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-bash:0.3.1
- tekton-pipelines-creds-init: registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-creds-init:0.3.1
- tekton-pipelines-entrypoint: registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-entrypoint:0.3.1
- tekton-pipelines-git-init: registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-git-init:0.3.1
- tekton-pipelines-gsutil: registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-gsutil:0.3.1
- tekton-pipelines-nop: registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-nop:0.3.1
- tekton-pipelines-kubeconfigwriter: registry.cn-hangzhou.aliyuncs.com/tekton-test/tekton-pipelines-kubeconfigwriter
