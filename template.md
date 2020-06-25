# [ Wheelman ]

[ Wheelman ] is a Clojure(script) library for [ making k8s suck less ].
 
 _"Think Fast. Drive Faster."_ 

## Quick Start

```clojure
  ;; one or more examples of how someone would use libname
  ;; inputs, outputs, workflow
  ;; is it just one function or more?

{:wheelman/type             :wheelman.objects/container
 :wheelman/name             "nginx"
 :wheelman.container/image  {:wheelman.container/registry   "http://..."
                             :wheelman.container/image-name "nginx"
                             :wheelman.container/label      "1.14.2"}}
```


## Objectives
- Get away from YAML
  - avoid indentation problems because *nobody* likes significant whitespace
  - allow for properly namespaced keys
- Validate ahead of time
  - highlight required fields
  - allow for properly namespaced keys
- DRY up your container stuff

## Limitations / Future Work

[ what would you like to have added or changed in your design? ]
[ any particular challenges? ]
[ was a data-driven approach suitable for this problem? ]
[ any of the reflection questions particularly relevant? ]


