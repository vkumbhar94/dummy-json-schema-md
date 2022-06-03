# Argus Helm Chart Configuration Schema Schema

```txt
http://example.com/example.json
```

The Argus Helm Chart Configuration Schema

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                      |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------- |
| Can be instantiated | Yes        | Unknown status | No           | Forbidden         | Forbidden             | none                | [values.schema.json](values.schema.json "open original schema") |

## Argus Helm Chart Configuration Schema Type

`object` ([Argus Helm Chart Configuration Schema](values.md))

## Argus Helm Chart Configuration Schema Default Value

The default value is:

```json
{}
```

## Argus Helm Chart Configuration Schema Examples

```json
{
  "accessID": "",
  "accessKey": "",
  "account": "",
  "clusterName": "",
  "clusterTreeParentID": 1,
  "image": {
    "repository": "logicmonitor/argus",
    "pullPolicy": "",
    "tag": ""
  },
  "nodeSelector": {},
  "affinity": {},
  "priorityClassName": "",
  "tolerations": [],
  "resources": {},
  "labels": {},
  "annotations": {},
  "replicas": 1,
  "resourceContainerID": 1,
  "log": {
    "level": "info"
  },
  "collectorsetcontroller": {
    "address": "collectorset-controller",
    "port": 50000
  },
  "proxy": {
    "url": "",
    "user": "",
    "pass": ""
  },
  "etcdDiscoveryToken": "",
  "ignoreSSL": false,
  "daemons": {
    "lmResourceSweeper": {
      "interval": "PT10M"
    },
    "lmCacheSync": {
      "interval": "PT1H"
    },
    "worker": {
      "poolSize": 10
    },
    "watcher": {
      "bulkSyncInterval": "PT30M",
      "runner": {
        "poolSize": 10,
        "backPressureQueueSizePerRunner": 10
      },
      "sysIpsWaitTimeout": "PT5M"
    }
  },
  "monitoring": {
    "disable": []
  },
  "lm": {
    "lmlogs": {
      "k8sevent": {
        "enable": false
      },
      "k8spodlog": {
        "enable": false
      }
    },
    "resource": {
      "globalDeleteAfterDuration": "P0DT0H0M0S",
      "alerting": {
        "disable": []
      }
    },
    "resourceGroup": {
      "extraProps": {
        "cluster": [],
        "nodes": [],
        "etcd": []
      }
    }
  },
  "filters": [],
  "selfMonitor": {
    "enable": false,
    "port": 2112
  },
  "debug": {
    "profiling": {
      "enable": false
    }
  },
  "collector": {
    "replicas": 1,
    "version": 0,
    "size": "small",
    "useEA": false,
    "lm": {
      "groupID": 0,
      "escalationChainID": 0
    },
    "image": {
      "repository": "logicmonitor/collector",
      "tag": "latest",
      "pullPolicy": ""
    },
    "proxy": {
      "url": "",
      "user": "",
      "pass": ""
    },
    "annotations": {},
    "labels": {},
    "statefulsetSpec": {
      "template": {
        "spec": {
          "nodeSelector": {},
          "tolerations": [],
          "priorityClassName": ""
        }
      }
    }
  },
  "kube-state-metrics": {
    "enabled": true,
    "replicas": 1,
    "collectors": [
      "daemonsets",
      "replicasets",
      "statefulsets",
      "persistentvolumes"
    ]
  },
  "global": {
    "accessID": "",
    "accessKey": "",
    "account": "",
    "proxy": {
      "url": "",
      "user": "",
      "pass": ""
    },
    "image": {
      "pullPolicy": "Always"
    },
    "collectorsetServiceNameSuffix": ""
  },
  "nameOverride": "",
  "fullnameOverride": "",
  "rbac": {
    "create": true
  },
  "serviceAccount": {
    "create": true
  }
}
```

# Argus Helm Chart Configuration Schema Properties

| Property                                          | Type      | Required | Nullable       | Defined by                                                                                                                                                               |
| :------------------------------------------------ | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [accessID](#accessid)                             | `string`  | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-logicmonitor-api-token-accessid.md "#/properties/accessID#/properties/accessID")                               |
| [accessKey](#accesskey)                           | `string`  | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-logicmonitor-api-token-accesskey.md "#/properties/accessKey#/properties/accessKey")                            |
| [account](#account)                               | `string`  | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-logicmonitor-account-name.md "#/properties/account#/properties/account")                                       |
| [clusterName](#clustername)                       | `string`  | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-friendly-cluster-name.md "#/properties/clusterName#/properties/clusterName")                                   |
| [clusterTreeParentID](#clustertreeparentid)       | `integer` | Required | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-clustertreeparentid.md "#/properties/clusterTreeParentID#/properties/clusterTreeParentID")                 |
| [image](#image)                                   | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema.md "#/properties/image#/properties/image")                                           |
| [nodeSelector](#nodeselector)                     | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-nodeselector.md "#/properties/nodeSelector#/properties/nodeSelector")                                          |
| [affinity](#affinity)                             | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-affinity.md "#/properties/affinity#/properties/affinity")                                                      |
| [priorityClassName](#priorityclassname)           | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-priorityclassname.md "#/properties/priorityClassName#/properties/priorityClassName")                           |
| [tolerations](#tolerations)                       | `array`   | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-tolerations.md "#/properties/tolerations#/properties/tolerations")                                             |
| [resources](#resources)                           | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-resource-limits-schema.md "#/properties/resources#/properties/resources")                            |
| [labels](#labels)                                 | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-extra-labels-schema.md "#/properties/labels#/properties/labels")                                     |
| [annotations](#annotations)                       | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-extra-annotations-schema.md "#/properties/annotations#/properties/annotations")                      |
| [replicas](#replicas)                             | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-replicas-schema.md "#/properties/replicas#/properties/replicas")                                           |
| [resourceContainerID](#resourcecontainerid)       | `integer` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-resourcecontainerid-schema.md "#/properties/resourceContainerID#/properties/resourceContainerID")          |
| [log](#log)                                       | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-log.md "#/properties/log#/properties/log")                                                                     |
| [collectorsetcontroller](#collectorsetcontroller) | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collectorsetcontroller-schema.md "#/properties/collectorsetcontroller#/properties/collectorsetcontroller") |
| [proxy](#proxy)                                   | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-proxy-schema.md "#/properties/proxy#/properties/proxy")                                                    |
| [etcdDiscoveryToken](#etcddiscoverytoken)         | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-etcd-discoverytoken-schema.md "#/properties/etcdDiscoveryToken#/properties/etcdDiscoveryToken")            |
| [ignoreSSL](#ignoressl)                           | `boolean` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-ignoressl-schema.md "#/properties/ignoreSSL#/properties/ignoreSSL")                                        |
| [daemons](#daemons)                               | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema.md "#/properties/daemons#/properties/daemons")                          |
| [monitoring](#monitoring)                         | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-monitoring-schema.md "#/properties/monitoring#/properties/monitoring")                                     |
| [lm](#lm)                                         | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations.md "#/properties/lm#/properties/lm")                                    |
| [filters](#filters)                               | `array`   | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-filters-schema.md "#/properties/filters#/properties/filters")                                              |
| [selfMonitor](#selfmonitor)                       | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-selfmonitor-schema.md "#/properties/selfMonitor#/properties/selfMonitor")                                  |
| [debug](#debug)                                   | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-debug-schema.md "#/properties/debug#/properties/debug")                                                    |
| [collector](#collector)                           | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema.md "#/properties/collector#/properties/collector")                                        |
| [kube-state-metrics](#kube-state-metrics)         | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-kube-state-metrics-schema.md "#/properties/kube-state-metrics#/properties/kube-state-metrics")             |
| [global](#global)                                 | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-global.md "#/properties/global#/properties/global")                                                            |
| [nameOverride](#nameoverride)                     | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-nameoverride-schema.md "#/properties/nameOverride#/properties/nameOverride")                               |
| [fullnameOverride](#fullnameoverride)             | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-fullnameoverride-schema.md "#/properties/fullnameOverride#/properties/fullnameOverride")                   |
| [rbac](#rbac)                                     | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-rbac-schema.md "#/properties/rbac#/properties/rbac")                                                       |
| [serviceAccount](#serviceaccount)                 | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-the-serviceaccount-schema.md "#/properties/serviceAccount#/properties/serviceAccount")                         |
| [imagePullSecrets](#imagepullsecrets)             | `array`   | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-imagepullsecrets.md "#/properties/imagePullSecrets#/properties/imagePullSecrets")                              |
| [probe](#probe)                                   | `object`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-properties-probe.md "#/properties/probe#/properties/probe")                                                               |

## accessID

The LogicMonitor API key ID.
NOTE: Always add surrounding double quotes to avoid special character parsing errors

`accessID`

*   is required

*   Type: `string` ([Logicmonitor API Token accessID](values-properties-logicmonitor-api-token-accessid.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-logicmonitor-api-token-accessid.md "#/properties/accessID#/properties/accessID")

### accessID Type

`string` ([Logicmonitor API Token accessID](values-properties-logicmonitor-api-token-accessid.md))

### accessID Examples

```json
""
```

## accessKey

# The LogicMonitor API key.

NOTE: Always add surrounding double quotes to avoid special character parsing errors

`accessKey`

*   is required

*   Type: `string` ([Logicmonitor API Token accessKey](values-properties-logicmonitor-api-token-accesskey.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-logicmonitor-api-token-accesskey.md "#/properties/accessKey#/properties/accessKey")

### accessKey Type

`string` ([Logicmonitor API Token accessKey](values-properties-logicmonitor-api-token-accesskey.md))

### accessKey Examples

```json
""
```

## account

The LogicMonitor account name.
Value should be trimmed from URL \_\_\_.logicmonitor.com
example: say, lmqauat.logicmonitor.com then "lmqauat" should be valid value

`account`

*   is required

*   Type: `string` ([Logicmonitor account name](values-properties-logicmonitor-account-name.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-logicmonitor-account-name.md "#/properties/account#/properties/account")

### account Type

`string` ([Logicmonitor account name](values-properties-logicmonitor-account-name.md))

### account Examples

```json
"lmqauat"
```

## clusterName

A unique name given to the cluster's resource group.
NOTE: do not change name once application deployed in cluster. If changed, breaks correlation at multiple places
example: Organised Resource group name of kubernetes resource tree generated as "Kubernetes Cluster: <clusterName>"

`clusterName`

*   is required

*   Type: `string` ([Friendly Cluster Name](values-properties-friendly-cluster-name.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-friendly-cluster-name.md "#/properties/clusterName#/properties/clusterName")

### clusterName Type

`string` ([Friendly Cluster Name](values-properties-friendly-cluster-name.md))

### clusterName Examples

```json
""
```

## clusterTreeParentID

clusterTreeParentID is a parent static resource group ID underneath the organised kubernetes resource tree gets created.
A static resource group with the mentioned ID should exit beforehand.

`clusterTreeParentID`

*   is required

*   Type: `integer` ([The clusterTreeParentID](values-properties-the-clustertreeparentid.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-clustertreeparentid.md "#/properties/clusterTreeParentID#/properties/clusterTreeParentID")

### clusterTreeParentID Type

`integer` ([The clusterTreeParentID](values-properties-the-clustertreeparentid.md))

### clusterTreeParentID Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### clusterTreeParentID Default Value

The default value is:

```json
1
```

### clusterTreeParentID Examples

```json
1
```

## image

The image holds the Argus docker image details.

`image`

*   is optional

*   Type: `object` ([Argus Docker Image Schema](values-properties-argus-docker-image-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-argus-docker-image-schema.md "#/properties/image#/properties/image")

### image Type

`object` ([Argus Docker Image Schema](values-properties-argus-docker-image-schema.md))

### image Default Value

The default value is:

```json
{}
```

### image Examples

```json
{
  "registry": "382028353997.dkr.ecr.us-west-2.amazonaws.com",
  "repository": "logicmonitor/argus",
  "pullPolicy": "Always",
  "tag": "v6"
}
```

## nodeSelector

NodeSelector is a selector which must be true for the pod to fit on a node. Selector which must match a node's labels for the pod to be scheduled on that node. More info: <https://kubernetes.io/docs/concepts/configuration/assign-pod-node/>

`nodeSelector`

*   is optional

*   Type: `object` ([nodeSelector](values-properties-nodeselector.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-nodeselector.md "#/properties/nodeSelector#/properties/nodeSelector")

### nodeSelector Type

`object` ([nodeSelector](values-properties-nodeselector.md))

### nodeSelector Default Value

The default value is:

```json
{}
```

### nodeSelector Examples

```json
{}
```

## affinity

It allows you to constrain which nodes your pod is eligible to be scheduled on.

`affinity`

*   is optional

*   Type: `object` ([affinity](values-properties-affinity.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-affinity.md "#/properties/affinity#/properties/affinity")

### affinity Type

`object` ([affinity](values-properties-affinity.md))

### affinity Default Value

The default value is:

```json
{}
```

### affinity Examples

```json
{}
```

## priorityClassName

The priority class name for Pod priority. If this parameter is set then user must have PriorityClass resource created otherwise Pod will be rejected.

`priorityClassName`

*   is optional

*   Type: `string` ([priorityClassName](values-properties-priorityclassname.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-priorityclassname.md "#/properties/priorityClassName#/properties/priorityClassName")

### priorityClassName Type

`string` ([priorityClassName](values-properties-priorityclassname.md))

### priorityClassName Examples

```json
""
```

## tolerations

tolerations are applied to pods, and allow the pods to schedule onto nodes with matching taints.

`tolerations`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-tolerations.md "#/properties/tolerations#/properties/tolerations")

### tolerations Type

unknown\[]

### tolerations Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

### tolerations Default Value

The default value is:

```json
[]
```

### tolerations Examples

```json
[]
```

## resources

The Argus pod resource limits

`resources`

*   is optional

*   Type: `object` ([The Argus resource limits schema](values-properties-the-argus-resource-limits-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-resource-limits-schema.md "#/properties/resources#/properties/resources")

### resources Type

`object` ([The Argus resource limits schema](values-properties-the-argus-resource-limits-schema.md))

### resources Default Value

The default value is:

```json
{}
```

### resources Examples

```json
{
  "limits": {
    "cpu": "1000m",
    "memory": "1Gi",
    "ephemeral-storage": "100Mi"
  },
  "requests": {
    "cpu": "1000m",
    "memory": "1Gi",
    "ephemeral-storage": "100Mi"
  }
}
```

## labels

Labels to apply on all objects created by Argus. Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: <http://kubernetes.io/docs/user-guide/labels>

`labels`

*   is optional

*   Type: `object` ([The Argus extra labels schema](values-properties-the-argus-extra-labels-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-extra-labels-schema.md "#/properties/labels#/properties/labels")

### labels Type

`object` ([The Argus extra labels schema](values-properties-the-argus-extra-labels-schema.md))

### labels Default Value

The default value is:

```json
{}
```

### labels Examples

```json
{}
```

## annotations

Annotations to apply on all objects created by Argus. Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: <http://kubernetes.io/docs/user-guide/annotations>

`annotations`

*   is optional

*   Type: `object` ([The Argus extra annotations schema](values-properties-the-argus-extra-annotations-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-extra-annotations-schema.md "#/properties/annotations#/properties/annotations")

### annotations Type

`object` ([The Argus extra annotations schema](values-properties-the-argus-extra-annotations-schema.md))

### annotations Default Value

The default value is:

```json
{}
```

### annotations Examples

```json
{}
```

## replicas

Argus Pod Replicas - defaults to 1, param is just for development purpose, do not increase more than one replicas in production

`replicas`

*   is optional

*   Type: `integer` ([The replicas schema](values-properties-the-replicas-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-replicas-schema.md "#/properties/replicas#/properties/replicas")

### replicas Type

`integer` ([The replicas schema](values-properties-the-replicas-schema.md))

### replicas Constraints

**maximum**: the value of this number must smaller than or equal to: `1`

**minimum**: the value of this number must greater than or equal to: `0`

### replicas Default Value

The default value is:

```json
1
```

### replicas Examples

```json
1
```

## resourceContainerID

The resourceContainerID is recommended to when Argus is being installed with non-admin user credentials.
The resourceContainerID is A parent resource group id that will hold all cluster resources under it.

`resourceContainerID`

*   is optional

*   Type: `integer` ([The resourceContainerID schema](values-properties-the-resourcecontainerid-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-resourcecontainerid-schema.md "#/properties/resourceContainerID#/properties/resourceContainerID")

### resourceContainerID Type

`integer` ([The resourceContainerID schema](values-properties-the-resourcecontainerid-schema.md))

### resourceContainerID Constraints

**minimum**: the value of this number must greater than or equal to: `1`

### resourceContainerID Default Value

The default value is:

```json
1
```

### resourceContainerID Examples

```json
1
```

## log

The Argus Log Configurations Schema

`log`

*   is optional

*   Type: `object` ([Log](values-properties-log.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-log.md "#/properties/log#/properties/log")

### log Type

`object` ([Log](values-properties-log.md))

### log Default Value

The default value is:

```json
{}
```

### log Examples

```json
{
  "level": "info"
}
```

## collectorsetcontroller

The Collectorset-Controller Configurations

`collectorsetcontroller`

*   is optional

*   Type: `object` ([The collectorsetcontroller schema](values-properties-the-collectorsetcontroller-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collectorsetcontroller-schema.md "#/properties/collectorsetcontroller#/properties/collectorsetcontroller")

### collectorsetcontroller Type

`object` ([The collectorsetcontroller schema](values-properties-the-collectorsetcontroller-schema.md))

### collectorsetcontroller Default Value

The default value is:

```json
{}
```

### collectorsetcontroller Examples

```json
{
  "address": "collectorset-controller",
  "port": 50000
}
```

## proxy

The Http/s proxy for Argus

`proxy`

*   is optional

*   Type: `object` ([The proxy schema](values-properties-the-proxy-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-proxy-schema.md "#/properties/proxy#/properties/proxy")

### proxy Type

`object` ([The proxy schema](values-properties-the-proxy-schema.md))

### proxy Default Value

The default value is:

```json
{}
```

### proxy Examples

```json
{
  "url": "",
  "user": "",
  "pass": ""
}
```

## etcdDiscoveryToken

The ETCD DiscoveryToken

`etcdDiscoveryToken`

*   is optional

*   Type: `string` ([The ETCD DiscoveryToken Schema](values-properties-the-etcd-discoverytoken-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-etcd-discoverytoken-schema.md "#/properties/etcdDiscoveryToken#/properties/etcdDiscoveryToken")

### etcdDiscoveryToken Type

`string` ([The ETCD DiscoveryToken Schema](values-properties-the-etcd-discoverytoken-schema.md))

### etcdDiscoveryToken Examples

```json
""
```

## ignoreSSL

Set flag to ignore ssl/tls validation

`ignoreSSL`

*   is optional

*   Type: `boolean` ([The ignoreSSL Schema](values-properties-the-ignoressl-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-ignoressl-schema.md "#/properties/ignoreSSL#/properties/ignoreSSL")

### ignoreSSL Type

`boolean` ([The ignoreSSL Schema](values-properties-the-ignoressl-schema.md))

### ignoreSSL Examples

```json
false
```

## daemons

The Argus Daemon configurations

`daemons`

*   is optional

*   Type: `object` ([The Argus Daemon configurations Schema](values-properties-the-argus-daemon-configurations-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-argus-daemon-configurations-schema.md "#/properties/daemons#/properties/daemons")

### daemons Type

`object` ([The Argus Daemon configurations Schema](values-properties-the-argus-daemon-configurations-schema.md))

### daemons Default Value

The default value is:

```json
{}
```

### daemons Examples

```json
{
  "lmResourceSweeper": {
    "interval": "10m"
  },
  "lmCacheSync": {
    "interval": "1h"
  },
  "worker": {
    "poolSize": 10
  },
  "watcher": {
    "bulkSyncInterval": "30m",
    "runner": {
      "poolSize": 10,
      "backPressureQueueSizePerRunner": 10
    },
    "sysIpsWaitTimeout": "5m"
  }
}
```

## monitoring

The Monitoring settings

`monitoring`

*   is optional

*   Type: `object` ([The monitoring schema](values-properties-the-monitoring-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-monitoring-schema.md "#/properties/monitoring#/properties/monitoring")

### monitoring Type

`object` ([The monitoring schema](values-properties-the-monitoring-schema.md))

### monitoring Default Value

The default value is:

```json
{}
```

### monitoring Examples

```json
{
  "disable": []
}
```

## lm

The Settings/Configurations which reflect on Logicmonitor Portal

`lm`

*   is optional

*   Type: `object` ([The Logicmonitor Portal Configurations](values-properties-the-logicmonitor-portal-configurations.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-logicmonitor-portal-configurations.md "#/properties/lm#/properties/lm")

### lm Type

`object` ([The Logicmonitor Portal Configurations](values-properties-the-logicmonitor-portal-configurations.md))

### lm Default Value

The default value is:

```json
{}
```

### lm Examples

```json
{
  "lmlogs": {
    "k8sevent": {
      "enable": false
    },
    "k8spodlog": {
      "enable": false
    }
  },
  "resource": {
    "globalDeleteAfterDuration": "P0DT0H0M0S",
    "alerting": {
      "disable": []
    }
  },
  "resourceGroup": {
    "extraProps": {
      "cluster": [],
      "nodes": [],
      "etcd": []
    }
  }
}
```

## filters

Set of filter rules to exclude from adding into Logimonitor

`filters`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-filters-schema.md "#/properties/filters#/properties/filters")

### filters Type

`string[]`

### filters Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

### filters Default Value

The default value is:

```json
[]
```

### filters Examples

```json
[
  "'!(type in (\"po\", (\"deploy\"), \"ep\"))'"
]
```

```json
[
  "'type == \"pod\" && [app.kubernetes.io/instance] != \"lm-container\""
]
```

## selfMonitor

Configurations to expose self monitor metrics in Openmetrics format

`selfMonitor`

*   is optional

*   Type: `object` ([The selfMonitor schema](values-properties-the-selfmonitor-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-selfmonitor-schema.md "#/properties/selfMonitor#/properties/selfMonitor")

### selfMonitor Type

`object` ([The selfMonitor schema](values-properties-the-selfmonitor-schema.md))

### selfMonitor Default Value

The default value is:

```json
{}
```

### selfMonitor Examples

```json
{
  "enable": false,
  "port": 2112
}
```

## debug

The Application debugging configurations

`debug`

*   is optional

*   Type: `object` ([The debug schema](values-properties-the-debug-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-debug-schema.md "#/properties/debug#/properties/debug")

### debug Type

`object` ([The debug schema](values-properties-the-debug-schema.md))

### debug Default Value

The default value is:

```json
{}
```

### debug Examples

```json
{
  "profiling": {
    "enable": false
  }
}
```

## collector

An explanation about the purpose of this instance.

`collector`

*   is optional

*   Type: `object` ([The collector schema](values-properties-the-collector-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-collector-schema.md "#/properties/collector#/properties/collector")

### collector Type

`object` ([The collector schema](values-properties-the-collector-schema.md))

### collector Default Value

The default value is:

```json
{}
```

### collector Examples

```json
{
  "replicas": 1,
  "version": 0,
  "size": "small",
  "useEA": false,
  "lm": {
    "groupID": 0,
    "escalationChainID": 0
  },
  "image": {
    "repository": "logicmonitor/collector",
    "tag": "latest",
    "pullPolicy": ""
  },
  "proxy": {
    "url": "",
    "user": "",
    "pass": ""
  },
  "annotations": {},
  "labels": {},
  "statefulsetSpec": {
    "template": {
      "spec": {
        "nodeSelector": {},
        "tolerations": [],
        "priorityClassName": ""
      }
    }
  }
}
```

## kube-state-metrics

An explanation about the purpose of this instance.

`kube-state-metrics`

*   is optional

*   Type: `object` ([The kube-state-metrics schema](values-properties-the-kube-state-metrics-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-kube-state-metrics-schema.md "#/properties/kube-state-metrics#/properties/kube-state-metrics")

### kube-state-metrics Type

`object` ([The kube-state-metrics schema](values-properties-the-kube-state-metrics-schema.md))

### kube-state-metrics Default Value

The default value is:

```json
{}
```

### kube-state-metrics Examples

```json
{
  "enabled": true,
  "replicas": 1,
  "collectors": [
    "daemonsets",
    "replicasets",
    "statefulsets",
    "persistentvolumes"
  ]
}
```

## global



`global`

*   is optional

*   Type: `object` ([Details](values-properties-global.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-global.md "#/properties/global#/properties/global")

### global Type

`object` ([Details](values-properties-global.md))

## nameOverride

An explanation about the purpose of this instance.

`nameOverride`

*   is optional

*   Type: `string` ([The nameOverride schema](values-properties-the-nameoverride-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-nameoverride-schema.md "#/properties/nameOverride#/properties/nameOverride")

### nameOverride Type

`string` ([The nameOverride schema](values-properties-the-nameoverride-schema.md))

### nameOverride Examples

```json
""
```

## fullnameOverride

An explanation about the purpose of this instance.

`fullnameOverride`

*   is optional

*   Type: `string` ([The fullnameOverride schema](values-properties-the-fullnameoverride-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-fullnameoverride-schema.md "#/properties/fullnameOverride#/properties/fullnameOverride")

### fullnameOverride Type

`string` ([The fullnameOverride schema](values-properties-the-fullnameoverride-schema.md))

### fullnameOverride Examples

```json
""
```

## rbac

An explanation about the purpose of this instance.

`rbac`

*   is optional

*   Type: `object` ([The rbac schema](values-properties-the-rbac-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-rbac-schema.md "#/properties/rbac#/properties/rbac")

### rbac Type

`object` ([The rbac schema](values-properties-the-rbac-schema.md))

### rbac Default Value

The default value is:

```json
{}
```

### rbac Examples

```json
{
  "create": true
}
```

## serviceAccount

An explanation about the purpose of this instance.

`serviceAccount`

*   is optional

*   Type: `object` ([The serviceAccount schema](values-properties-the-serviceaccount-schema.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-the-serviceaccount-schema.md "#/properties/serviceAccount#/properties/serviceAccount")

### serviceAccount Type

`object` ([The serviceAccount schema](values-properties-the-serviceaccount-schema.md))

### serviceAccount Default Value

The default value is:

```json
{}
```

### serviceAccount Examples

```json
{
  "create": true
}
```

## imagePullSecrets

ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec. If specified, these secrets will be passed to individual puller implementations for them to use. For example, in the case of docker, only DockerConfig type secrets are honored. More info: <https://kubernetes.io/docs/concepts/containers/images#specifying-imagepullsecrets-on-a-pod>

`imagePullSecrets`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-imagepullsecrets.md "#/properties/imagePullSecrets#/properties/imagePullSecrets")

### imagePullSecrets Type

unknown\[]

## probe

The container probe configuration schema

`probe`

*   is optional

*   Type: `object` ([Details](values-properties-probe.md))

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-properties-probe.md "#/properties/probe#/properties/probe")

### probe Type

`object` ([Details](values-properties-probe.md))

# Argus Helm Chart Configuration Schema Definitions

## Definitions group toleration

Reference this group by using

```json
{"$ref":"http://example.com/example.json#/definitions/toleration"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group propopts

Reference this group by using

```json
{"$ref":"http://example.com/example.json#/definitions/propopts"}
```

| Property              | Type      | Required | Nullable       | Defined by                                                                                                                                                              |
| :-------------------- | :-------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)         | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-definitions-propopts-properties-name.md "http://example.com/example.json#/definitions/propopts/properties/name")         |
| [value](#value)       | `string`  | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-definitions-propopts-properties-value.md "http://example.com/example.json#/definitions/propopts/properties/value")       |
| [override](#override) | `boolean` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-definitions-propopts-properties-override.md "http://example.com/example.json#/definitions/propopts/properties/override") |

### name



`name`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-definitions-propopts-properties-name.md "http://example.com/example.json#/definitions/propopts/properties/name")

#### name Type

`string`

#### name Constraints

**minimum length**: the minimum number of characters for this string is: `1`

### value



`value`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-definitions-propopts-properties-value.md "http://example.com/example.json#/definitions/propopts/properties/value")

#### value Type

`string`

#### value Constraints

**minimum length**: the minimum number of characters for this string is: `0`

### override



`override`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-definitions-propopts-properties-override.md "http://example.com/example.json#/definitions/propopts/properties/override")

#### override Type

`boolean`

#### override Default Value

The default value is:

```json
true
```

## Definitions group propoptsarray

Reference this group by using

```json
{"$ref":"http://example.com/example.json#/definitions/propoptsarray"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group io.k8s.apimachinery.pkg.api.resource.Quantity

Reference this group by using

```json
{"$ref":"http://example.com/example.json#/definitions/io.k8s.apimachinery.pkg.api.resource.Quantity"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group io.k8s.api.core.v1.LocalObjectReference

Reference this group by using

```json
{"$ref":"http://example.com/example.json#/definitions/io.k8s.api.core.v1.LocalObjectReference"}
```

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                               |
| :-------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name-1) | `string` | Optional | cannot be null | [Argus Helm Chart Configuration Schema](values-definitions-iok8sapicorev1localobjectreference-properties-name.md "http://example.com/example.json#/definitions/io.k8s.api.core.v1.LocalObjectReference/properties/name") |

### name

Name of the referent. More info: <https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names>

`name`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Argus Helm Chart Configuration Schema](values-definitions-iok8sapicorev1localobjectreference-properties-name.md "http://example.com/example.json#/definitions/io.k8s.api.core.v1.LocalObjectReference/properties/name")

#### name Type

`string`
