# README

## Top-level Schemas

*   [The root schema](./values.md "The root schema comprises the entire JSON document") – `http://example.com/example.json`

## Other Schemas

### Objects

*   [Log](./values-properties-log.md "Log Configurations") – `#/properties/log#/properties/log`

*   [The alerting schema](./values-properties-the-lm-schema-properties-the-resource-schema-properties-the-alerting-schema.md "Alerting settings to apply on resource groups, only cluster scoped resources are valid here, other gets ignored") – `#/properties/lm/properties/resource/properties/alerting#/properties/lm/properties/resource/properties/alerting`

*   [The annotations schema](./values-properties-the-collector-schema-properties-the-annotations-schema.md "An explanation about the purpose of this instance") – `#/properties/collector/properties/annotations#/properties/collector/properties/annotations`

*   [The collector schema](./values-properties-the-collector-schema.md "An explanation about the purpose of this instance") – `#/properties/collector#/properties/collector`

*   [The debug schema](./values-properties-the-debug-schema.md "Application debug configurations") – `#/properties/debug#/properties/debug`

*   [The extraProps schema](./values-properties-the-lm-schema-properties-the-resourcegroup-schema-properties-the-extraprops-schema.md "Extra Properties to add upon resource groups, only cluster scoped resources are valid, for rest others use namespace labels") – `#/properties/lm/properties/resourceGroup/properties/extraProps#/properties/lm/properties/resourceGroup/properties/extraProps`

*   [The image schema](./values-properties-the-image-schema.md "An explanation about the purpose of this instance") – `#/properties/image#/properties/image`

*   [The image schema](./values-properties-the-collector-schema-properties-the-image-schema.md "An explanation about the purpose of this instance") – `#/properties/collector/properties/image#/properties/collector/properties/image`

*   [The image schema](./values-properties-global-properties-the-image-schema.md "An explanation about the purpose of this instance") – `#/properties/global/properties/image#/properties/global/properties/image`

*   [The k8sevent schema](./values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8sevent-schema.md "Kubernetes Events collection configurations") – `#/properties/lm/properties/lmlogs/properties/k8sevent#/properties/lm/properties/lmlogs/properties/k8sevent`

*   [The k8spodlog schema](./values-properties-the-lm-schema-properties-the-lmlogs-schema-properties-the-k8spodlog-schema.md "Kubernetes Pod Logs collection configurations") – `#/properties/lm/properties/lmlogs/properties/k8spodlog#/properties/lm/properties/lmlogs/properties/k8spodlog`

*   [The kube-state-metrics schema](./values-properties-the-kube-state-metrics-schema.md "An explanation about the purpose of this instance") – `#/properties/kube-state-metrics#/properties/kube-state-metrics`

*   [The labels schema](./values-properties-the-collector-schema-properties-the-labels-schema.md "An explanation about the purpose of this instance") – `#/properties/collector/properties/labels#/properties/collector/properties/labels`

*   [The lm schema](./values-properties-the-lm-schema.md "Settings reflect on Logicmonitor Portal") – `#/properties/lm#/properties/lm`

*   [The lm schema](./values-properties-the-collector-schema-properties-the-lm-schema.md "An explanation about the purpose of this instance") – `#/properties/collector/properties/lm#/properties/collector/properties/lm`

*   [The lmlogs schema](./values-properties-the-lm-schema-properties-the-lmlogs-schema.md "Logicmonitor Logs collection settings") – `#/properties/lm/properties/lmlogs#/properties/lm/properties/lmlogs`

*   [The monitoring schema](./values-properties-the-monitoring-schema.md "Monitoring settings") – `#/properties/monitoring#/properties/monitoring`

*   [The profiling schema](./values-properties-the-debug-schema-properties-the-profiling-schema.md "Profile generation configurations") – `#/properties/debug/properties/profiling#/properties/debug/properties/profiling`

*   [The proxy schema](./values-properties-the-collector-schema-properties-the-proxy-schema.md "An explanation about the purpose of this instance") – `#/properties/collector/properties/proxy#/properties/collector/properties/proxy`

*   [The rbac schema](./values-properties-the-rbac-schema.md "An explanation about the purpose of this instance") – `#/properties/rbac#/properties/rbac`

*   [The resource schema](./values-properties-the-lm-schema-properties-the-resource-schema.md "An explanation about the purpose of this instance") – `#/properties/lm/properties/resource#/properties/lm/properties/resource`

*   [The resourceGroup schema](./values-properties-the-lm-schema-properties-the-resourcegroup-schema.md "Resource Group Settings") – `#/properties/lm/properties/resourceGroup#/properties/lm/properties/resourceGroup`

*   [The resources schema](./values-properties-the-resources-schema.md "resources are Pod resource limits") – `#/properties/resources#/properties/resources`

*   [The runner schema](./values-properties-daemons-properties-watcher-properties-the-runner-schema.md "configurations for parallel runners to process watcher events") – `#/properties/daemons/properties/watcher/properties/runner#/properties/daemons/properties/watcher/properties/runner`

*   [The selfMonitor schema](./values-properties-the-selfmonitor-schema.md "Configurations to expose self monitor metrics in Openmetrics format") – `#/properties/selfMonitor#/properties/selfMonitor`

*   [The serviceAccount schema](./values-properties-the-serviceaccount-schema.md "An explanation about the purpose of this instance") – `#/properties/serviceAccount#/properties/serviceAccount`

*   [Untitled object in The root schema](./values-properties-the-resources-schema-properties-limits.md "Limits describes the maximum amount of compute resources allowed") – `#/properties/resources/properties/limits#/properties/resources/properties/limits`

*   [Untitled object in The root schema](./values-properties-the-resources-schema-properties-requests.md "Requests describes the minimum amount of compute resources required") – `#/properties/resources/properties/requests#/properties/resources/properties/requests`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec.md "The collector StatefulSet specification for customizations") – `#/properties/collector/properties/statefulsetspec#/properties/collector/properties/statefulsetSpec`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template.md) – `#/properties/collector/properties/statefulsetspec/properties/template#/properties/collector/properties/statefulsetSpec/properties/template`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec.md) – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items.md "A single application container that you want to run within a pod") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources.md "Compute Resources required by this container") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-limits.md "Limits describes the maximum amount of compute resources allowed") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources/properties/limits`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items-properties-resources-properties-requests.md "Requests describes the minimum amount of compute resources required") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers/items/properties/resources/properties/requests`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig.md "PodDNSConfig defines the DNS parameters of a pod in addition to those generated from DNSPolicy") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/dnsConfig#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-options-items.md "PodDNSConfigOption defines DNS resolver options of a pod") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/options/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/options/items`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items.md "HostAlias holds the mapping between IP and hostnames that will be injected as an entry in the pod's hosts file") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases/items`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodeselector.md "NodeSelector is a selector which must be true for the pod to fit on a node") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/nodeselector#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/nodeSelector`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items.md "Volume represents a named volume in a pod that may be accessed by any container in the pod") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-awselasticblockstore.md "Represents a Persistent Disk resource in AWS") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/awselasticblockstore#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/awsElasticBlockStore`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-azuredisk.md "AzureDisk represents an Azure Data Disk mount on the host and bind mount to the pod") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/azuredisk#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/azureDisk`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap.md "Adapts a ConfigMap into a volume") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items-items.md "Maps a string key to a path within a volume") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/configmap/items/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items/items`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-emptydir.md "Represents an empty directory for a pod") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/emptydir#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/emptyDir`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-hostpath.md "Represents a host path mapped into a pod") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/hostpath#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/hostPath`

*   [Untitled object in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-persistentvolumeclaim.md "PersistentVolumeClaimVolumeSource references the user's PVC in the same namespace") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/persistentvolumeclaim#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/persistentVolumeClaim`

*   [Untitled object in The root schema](./values-properties-global.md) – `#/properties/global#/properties/global`

*   [Untitled object in The root schema](./values-definitions-toleration-oneof-0.md) – `http://example.com/example.json#/definitions/toleration/oneOf/0`

*   [Untitled object in The root schema](./values-definitions-toleration-oneof-1.md) – `http://example.com/example.json#/definitions/toleration/oneOf/1`

*   [Untitled object in The root schema](./values-definitions-propopts.md) – `http://example.com/example.json#/definitions/propopts`

*   [Untitled object in The root schema](./values-definitions-iok8sapicorev1localobjectreference.md "LocalObjectReference contains enough information to let you locate the referenced object inside the same namespace") – `http://example.com/example.json#/definitions/io.k8s.api.core.v1.LocalObjectReference`

*   [affinity](./values-properties-affinity.md "It allows you to constrain which nodes your pod is eligible to be scheduled on") – `#/properties/affinity#/properties/affinity`

*   [collectorsetcontroller](./values-properties-collectorsetcontroller.md "Collectorset-Controller Configurations") – `#/properties/collectorsetcontroller#/properties/collectorsetcontroller`

*   [daemons](./values-properties-daemons.md "Daemon configurations") – `#/properties/daemons#/properties/daemons`

*   [extraAnnotations](./values-properties-extraannotations.md "Annotations to apply on all objects created by Argus") – `#/properties/annotations#/properties/annotations`

*   [extraLabels](./values-properties-extralabels.md "Labels to apply on all objects created by Argus") – `#/properties/labels#/properties/labels`

*   [lmCacheSync](./values-properties-daemons-properties-lmcachesync.md "Cache Sync using LM resources configurations") – `#/properties/daemons/properties/lmCacheSync#/properties/daemons/properties/lmCacheSync`

*   [lmResourceSweeper](./values-properties-daemons-properties-lmresourcesweeper.md "LM Resource sweeper configurations") – `#/properties/daemons/properties/lmResourceSweeper#/properties/daemons/properties/lmResourceSweeper`

*   [nodeSelector](./values-properties-nodeselector.md "NodeSelector is a selector which must be true for the pod to fit on a node") – `#/properties/nodeSelector#/properties/nodeSelector`

*   [proxy](./values-properties-proxy.md "Http/s proxy") – `#/properties/proxy#/properties/proxy`

*   [watcher](./values-properties-daemons-properties-watcher.md "Kubernetes watcher configurations") – `#/properties/daemons/properties/watcher#/properties/daemons/properties/watcher`

*   [worker](./values-properties-daemons-properties-worker.md "Worker configurations") – `#/properties/daemons/properties/worker#/properties/daemons/properties/worker`

### Arrays

*   [Properties to apply upon node resource group](./values-properties-the-lm-schema-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-properties-to-apply-upon-node-resource-group.md) – `#/properties/lm/properties/resourceGroup/properties/extraProps/properties/nodes#/properties/lm/properties/resourceGroup/properties/extraProps/properties/nodes`

*   [The cluster schema](./values-properties-the-lm-schema-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-the-cluster-schema.md "Properties to apply upon cluster tree root group") – `#/properties/lm/properties/resourceGroup/properties/extraProps/properties/cluster#/properties/lm/properties/resourceGroup/properties/extraProps/properties/cluster`

*   [The collectors schema](./values-properties-the-kube-state-metrics-schema-properties-the-collectors-schema.md "An explanation about the purpose of this instance") – `#/properties/kube-state-metrics/properties/collectors#/properties/kube-state-metrics/properties/collectors`

*   [The disable schema](./values-properties-the-monitoring-schema-properties-the-disable-schema.md "Set of resource names to disable monitoring for") – `#/properties/monitoring/properties/disable#/properties/monitoring/properties/disable`

*   [The disable schema](./values-properties-the-lm-schema-properties-the-resource-schema-properties-the-alerting-schema-properties-the-disable-schema.md "Set of resources to disable alerting on") – `#/properties/lm/properties/resource/properties/alerting/properties/disable#/properties/lm/properties/resource/properties/alerting/properties/disable`

*   [The etcd schema](./values-properties-the-lm-schema-properties-the-resourcegroup-schema-properties-the-extraprops-schema-properties-the-etcd-schema.md "Properties to apply upon etcd resource group") – `#/properties/lm/properties/resourceGroup/properties/extraProps/properties/etcd#/properties/lm/properties/resourceGroup/properties/extraProps/properties/etcd`

*   [The filters schema](./values-properties-the-filters-schema.md "Set of filter rules to exclude from adding into Logimonitor") – `#/properties/filters#/properties/filters`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers.md) – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-nameservers.md "A list of DNS name server IP addresses") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/nameservers#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/nameservers`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-options.md "A list of DNS resolver options") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/options#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/options`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig-properties-searches.md "A list of DNS search domains for host-name lookup") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers/properties/searches#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig/properties/searches`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases.md "HostAliases is an optional list of hosts and IPs that will be injected into the pod's hosts file if specified") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items-properties-hostnames.md "Hostnames for the above IP address") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases/items/properties/hostnames`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-tolerations.md) – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/tolerations#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/tolerations`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes.md "List of volumes that can be mounted by containers belonging to the pod") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes`

*   [Untitled array in The root schema](./values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items-properties-configmap-properties-items.md "If unspecified, each key-value pair in the Data field of the referenced ConfigMap will be projected into the volume as a file whose name is the key and content is the value") – `#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes/items/properties/items#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes/items/properties/configMap/properties/items`

*   [Untitled array in The root schema](./values-properties-global-properties-imagepullsecrets.md "ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec") – `#/properties/global#/properties/global/properties/imagePullSecrets`

*   [Untitled array in The root schema](./values-properties-imagepullsecrets.md "ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec") – `http://example.com/example.json#/properties/imagePullSecrets`

*   [Untitled array in The root schema](./values-definitions-propoptsarray.md) – `http://example.com/example.json#/definitions/propoptsarray`

*   [tolerations](./values-properties-tolerations.md "tolerations are applied to pods, and allow the pods to schedule onto nodes with matching taints") – `#/properties/tolerations#/properties/tolerations`

## Version Note

The schemas linked above follow the JSON Schema Spec version: `http://json-schema.org/draft-07/schema`
