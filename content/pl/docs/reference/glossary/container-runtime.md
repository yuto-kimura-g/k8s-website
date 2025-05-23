---
title: Container Runtime
id: container-runtime
date: 2019-06-05
full_link: /docs/setup/production-environment/container-runtimes
short_description: >
 *Container runtime* to oprogramowanie zajmujące się uruchamianiem kontenerów.

aka:
tags:
- fundamental
- workload
---
 Podstawowy komponent umożliwiający efektywne uruchamianie kontenerów w Kubernetesie.
Odpowiada za zarządzanie uruchamianiem i cyklem życia kontenerów w środowisku Kubernetes.

<!--more-->

Kubernetes obsługuje różne *container runtimes*:
{{< glossary_tooltip term_id="containerd" >}}, {{< glossary_tooltip term_id="cri-o" >}}
oraz każdą implementację zgodną z [Kubernetes CRI (Container Runtime
Interface)](https://github.com/kubernetes/community/blob/master/contributors/devel/sig-node/container-runtime-interface.md).
