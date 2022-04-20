# Untitled object in Logicmonitor Argus Helm Chart Values Schema Schema

```txt
#/properties/collector/properties/statefulsetspec/properties/template/properties/spec#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [values.schema.json\*](values.schema.json "open original schema") |

## spec Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec.md))

# spec Properties

| Property                                | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                  |
| :-------------------------------------- | :-------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [containers](#containers)               | `array`   | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers")                      |
| [dnsConfig](#dnsconfig)                 | `object`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/dnsConfig#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig")                         |
| [dnsPolicy](#dnspolicy)                 | `string`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnspolicy.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/dnsPolicy#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsPolicy")                         |
| [hostAliases](#hostaliases)             | `array`   | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases")                   |
| [nodeName](#nodename)                   | `string`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodename.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/nodename#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/nodeName")                            |
| [nodeSelector](#nodeselector)           | `object`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodeselector.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/nodeselector#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/nodeSelector")                |
| [priority](#priority)                   | `integer` | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-priority.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/priority#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/priority")                            |
| [priorityClassName](#priorityclassname) | `string`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-priorityclassname.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/priorityclassname#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/priorityClassName") |
| [restartPolicy](#restartpolicy)         | `string`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-restartpolicy.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/restartpolicy#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/restartPolicy")             |
| [schedulerName](#schedulername)         | `string`  | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-schedulername.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/schedulername#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/schedulerName")             |
| [tolerations](#tolerations)             | `array`   | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-tolerations.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/tolerations#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/tolerations")                   |
| [volumes](#volumes)                     | `array`   | Optional | cannot be null | [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes")                               |

## containers



`containers`

*   is optional

*   Type: `object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/containers#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/containers")

### containers Type

`object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-containers-items.md))

## dnsConfig

PodDNSConfig defines the DNS parameters of a pod in addition to those generated from DNSPolicy.

`dnsConfig`

*   is optional

*   Type: `object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/dnsConfig#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsConfig")

### dnsConfig Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnsconfig.md))

## dnsPolicy

Set DNS policy for the pod. Defaults to "ClusterFirst". Valid values are 'ClusterFirstWithHostNet', 'ClusterFirst', 'Default' or 'None'. DNS parameters given in DNSConfig will be merged with the policy selected with DNSPolicy. To have DNS options set along with hostNetwork, you have to specify DNS policy explicitly to 'ClusterFirstWithHostNet'.

`dnsPolicy`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-dnspolicy.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/dnsPolicy#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/dnsPolicy")

### dnsPolicy Type

`string`

## hostAliases

HostAliases is an optional list of hosts and IPs that will be injected into the pod's hosts file if specified. This is only valid for non-hostNetwork pods.

`hostAliases`

*   is optional

*   Type: `object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/hostAliases#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/hostAliases")

### hostAliases Type

`object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-hostaliases-items.md))

## nodeName

NodeName is a request to schedule this pod onto a specific node. If it is non-empty, the scheduler simply schedules this pod onto that node, assuming that it fits resource requirements.

`nodeName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodename.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/nodename#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/nodeName")

### nodeName Type

`string`

## nodeSelector

NodeSelector is a selector which must be true for the pod to fit on a node. Selector which must match a node's labels for the pod to be scheduled on that node. More info: <https://kubernetes.io/docs/concepts/configuration/assign-pod-node/>

`nodeSelector`

*   is optional

*   Type: `object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodeselector.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodeselector.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/nodeselector#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/nodeSelector")

### nodeSelector Type

`object` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-nodeselector.md))

## priority

The priority value. Various system components use this field to find the priority of the pod. When Priority Admission Controller is enabled, it prevents users from setting this field. The admission controller populates this field from PriorityClassName. The higher the value, the higher the priority.

`priority`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-priority.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/priority#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/priority")

### priority Type

`integer`

### priority Constraints

**unknown format**: the value of this string must follow the format: `int32`

## priorityClassName

If specified, indicates the pod's priority. "system-node-critical" and "system-cluster-critical" are two special keywords which indicate the highest priorities with the former being the highest priority. Any other name must be defined by creating a PriorityClass object with that name. If not specified, the pod priority will be default or zero if there is no default.

`priorityClassName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-priorityclassname.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/priorityclassname#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/priorityClassName")

### priorityClassName Type

`string`

## restartPolicy

Restart policy for all containers within the pod. One of Always, OnFailure, Never. Default to Always. More info: <https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/#restart-policy>

`restartPolicy`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-restartpolicy.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/restartpolicy#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/restartPolicy")

### restartPolicy Type

`string`

## schedulerName

If specified, the pod will be dispatched by specified scheduler. If not specified, the pod will be dispatched by default scheduler.

`schedulerName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-schedulername.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/schedulername#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/schedulerName")

### schedulerName Type

`string`

## tolerations



`tolerations`

*   is optional

*   Type: unknown\[]

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-tolerations.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/tolerations#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/tolerations")

### tolerations Type

unknown\[]

### tolerations Constraints

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## volumes

List of volumes that can be mounted by containers belonging to the pod. More info: <https://kubernetes.io/docs/concepts/storage/volumes>

`volumes`

*   is optional

*   Type: `object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items.md))

*   cannot be null

*   defined in: [Logicmonitor Argus Helm Chart Values Schema](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes.md "#/properties/collector/properties/statefulsetspec/properties/template/properties/spec/properties/volumes#/properties/collector/properties/statefulsetSpec/properties/template/properties/spec/properties/volumes")

### volumes Type

`object[]` ([Details](values-properties-the-collector-schema-properties-statefulsetspec-properties-template-properties-spec-properties-volumes-items.md))
