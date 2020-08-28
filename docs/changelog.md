# Changelog

## [v2.11.0](https://github.com/harbur/kubernetic/milestone/19?closed=1)

* feature \#213 Watch status of workloads
* feature \#212 Group impersonation
* feature \#211 Add Application Backlink
* feature \#210 Filter logs by keywords
* feature \#208 Add Application StatusTab
* feature \#207 User impersonation enterprise
* feature \#204 Add create ArgoCD CRD options enterprise
* feature \#206 Dashboard display info for users with reduced privilages
* feature \#205 Add create application form enterprise
* feature \#203 Support for Network Policies
* feature \#201 For Logs view, it would be nice if we could apply a grep to the log stream
* fix \#199 2.10.0 Workloads > Deployments > Rollouts sorting is string based not numeric bug

## [v2.10.0](https://github.com/harbur/kubernetic/milestone/18?closed=1)

* feature \#196 Add Terminal support for all workloads
* feature \#194 Create addon for metrics-server
* feature \#195 Create addon for metrics-scraper
* feature \#176 Create addon for operators
* feature \#193 Expose usage metrics of cpu and memory
* feature \#197 Expose time-series graph of cpu and memory
* feature \#192 Add Preview Button on all Create screens
* feature \#143 Descriptions when creating things
* feature \#186 Make some things configurable
* fix \#170 RBAC Group Permissions Issue
* fix \#173 Common tab groups should be open by default
* fix \#161 MacOS: missing icon in status bar
* fix \#183 blank page of node describe from pods specifications
* fix \#158 Accessibility issue with context and namespace drop-down menus
* fix \#179 Pod Terminal restarts if Kubernetic get focus again
* fix \#171 Pod OutOfcpu status reported as Unknown in Kubernetic

## [v2.9.0](https://github.com/harbur/kubernetic/milestone/16?closed=1)

* fix \#151 Network connection seems broken after standby
* fix \#162 The list is not updated after deleting a resource
* fix \#160 2.7.0 - Custom Resources: Searching/Filtering doesn't work, don't load
* fix \#138 Support for helm TLS and tiller namespace

## [v2.8.1](https://github.com/harbur/kubernetic/milestone/17?closed=1)

* fix \#165 Unable to delete jobs after Kubernetic 2.8.0 update
* fix \#163 Portforward no longer working after update

## [v2.8.0](https://github.com/harbur/kubernetic/milestone/15?closed=1)

* feature \#121 \[Feature request] Helm 3 support 
* feature \#107 \[Feature Request] Show allocated resources (requests and limits) per node
* feature \#50 Events section
* feature \#78 \[Feature] Refresh button and refresh rate option for current page
* feature \#142 Customize pagination
* feature \#159 \[Feature Request] Support for global custom resources
* feature \#99 Logs should auto scroll
* feature \#153 \[New feature] View init-containers in pods
* feature \#89 \[FEATURE REQUEST] Support for previous logs display
* fix \#155 \[Feature request] Scaling terminal/items screen 
* dup \#156 \[Feature Request] show previous logs

## [v2.7.0](https://github.com/harbur/kubernetic/milestone/14?closed=1)

* feature \#108 \[Feature Request] Support for custom resources (kind)
* feature \#109 \[Feature Request] Support for rollout command
* feature \#149 \[Feature request] Terminal - Selecting a container
* feature \#95 RBAC editing
* bug \#157 CronJobs showing data for wrong context
* bug \#145 Strange behavior when select multiple objects
* bug \#146 Limitranges - incorrectly reporting
* dup \#81 Display CRD's

## v2.6.0

* feature \#45 terminal for pod
* feature \#102 service port forward support
* feature \#94 support cronjob
* bug \#147 automatic update not working properly
* bug \#144 blank screen - when clicking PV specifications
* dup \#126 log into the pod

## v2.5.0

* \#103 OIDC authentication seems broken in 2.3.0
* \#28 Implement support for multiple kubeconfig files
* \#110 \[WINDOWS\] Can't set properly kubeconfig file
* \#56 Not supporting KUBECONFIG, error from missing config file
* \#92 Weird results with multiple contexts
* \#117 Showing pods log in version 2.4.1
* \#93 \[FEATURE REQUEST\] Support HTTP Proxies
* \#124 Cannot login
* \#130 \[Feature request\] Give feedback if the connection is established between app & cluster
* \#134 percentage calculation incorrect (limits, quota % used)

## v2.4.3

Fixes:
* \#128 namespace changes to default at start
* Fix "Show last x lines" option on Logs screen

Features:
* Show container names on Logs screen
* Add dropdown filter for logs by Pod & Container
* Show logs on Deployments, Replicasets, ReplicationControllers, Jobs, CronJobs, DaemonSets & StatefulSets


## v2.4.2

Fixes:
* \#127 Logs not visible after switching context in kubernetic
* \#120 it just freezes
* \#117 Showing pods log in version 2.4.1


## v2.4.1

Fixes:

* \#115 After upgrade cannot connect to Azure cluster

## v2.4.0

Fixes:

* \#57 Support EKS clusters
* \#104 Freezing When Switching Contexts
* \#105 Not able to connect to GKE clusters
* \#106 Unable to connect to rancher/k3s cluster
* \#113 kubernetic 2.3.0 can't view deployments on kubelet 1.16

Refactor:

* Switch Backend from Node to Go client for better stability

## v2.3.0

Features:

* \#57 Support EKS clusters

## v2.1.0

Features:

* Add Create actions per each resource

## v2.0.16

Bug fixes:

* \#58 Could not start kubernetic on Win10

## v2.0.15

Features:

* Add Edit resources action
* \#49 Add support for StatefulSets

Bug fixes:

* \#53 Crash if ca-cert is relative to the ~/.kube directory
* \#52 App should not launch on full-screen mode
* \#51 Logs are missing

## v2.0.14

* Added Icon for Windows app
* Added Side Menu counter for items

## v2.0.13

* If context doesn't have namespace do not add it on TopMenu
* Logs now cannot be viewed if Pod is still Pending
* Add Scrollbar on Settings screens
* Added support for RBAC connection

## v2.0.12

* Issue \#38 Fixing issue on Windows finding ~/.kube/config
* Helm list shows now only releases on specific namespace
* Added view of children generated by Helm Release
* Fix Logs issue with first lines
* Fix Chart Deploy setting custom values

## v2.0.11

* Issue \#38: Removed try/catch to show origin of error
* Added Ready and Status info on Helm Releases

## v2.0.10

* Added support syncing with kubectx and kubens
* Added Popup on Contexts with context details
* Show last x lines on Logs screen
* Fixes Logs scrolling
* Charts are now shown on first click

## v2.0.9

* Fixed issue finding the PATH to helm

## v2.0.8

* If an item is deleted, return to List screen
* Fixed issue with logs
* Added monitoring of ~/.kube/config to update automatically
* Add support for deletion propagation

## v2.0.7

* Added support for GKE environments
* Added possibility to connect using insecure-tls

## v2.0.6

* Fix running app when packaged
* Update package name to Kubernetic

## v2.0.5

* Added connection status on Top Menu
* Added counter of items on Breadcrumb
* Added loading state for helm init
* Added minWidth on Window
* Now ~/.kubernetic/tmp is created if it doesn't exist

## v2.0.4

* Added networking issue message when updating if offline
* Fix issue with deleting resources

## v2.0.3

* Fixed windowManager to show properly initial screen

## v2.0.2

* Fix issue with Modal not opening

## v2.0.1

* Update of Dependencies

## v2.0.0

* Major refactor migrating from Angular to React

## v0.8.0

* Issue \#8 Fix visual problem on labels
* Issue \#7 Added Token-based Authentication
* Added support for username/password authentication
* Now deployment is separate screen instead of popup
* Remove angular $$hashkeys on YAML view
* Now Breadcrumb texts are in plural
* Links in Dashboard now works
* Breadcrumb titles are now links
* Image version if not defined is 'latest'

## v0.7.1

* Issue \#19 Prompt to configure kubectl if no existing cluster

## v0.7.0

* Added support for auto-update of Kubernetic
* Added Windows distro
* Issue \#18 Added better parsing of Chart.yaml
* Added connectivity to GCP kubernetes clusters

## v0.6.0

* Updated clusters and namespaces UI
* Fix Chart deployment dialog
* Improve Chart & Release UI

## v0.5.0

* Added status for Nodes
* Updated helm v2.0.0
* Removed Kubectl binary
* Updated Ready state for deployment & replicasets
* Improve performance
* Added cordon button on Nodes
* Added group actions
* Added ingress status

## v0.4.0

* Added possibility to import local-dir Repository
* Added Preview button on Pods
* Added Chart deployment parameters: Release name & Namespace
* Upgrade helm to 2.0.0-alpha.5
* Added error message when chart deploy fails
* Added confirmation for deleting a Chart release

## v0.3.0

* Added Search field
* Added confirmation popup for deletions
* Added Code Editor
* Added Update Image button on Deployments

## v0.2.0

* Add dialog to install Helm on Cluster
* Activate Keyboard Shortcuts

## v0.1.0

Initial Release
