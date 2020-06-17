# # 5 GitOps
https://lastcoolnameleft.github.io/WhatTheHack/023-AdvancedKubernetes/Student/05-gitops.html

> TODO: Step-by-Step, Git User Name? 
https://github.com/fluxcd/flux/blob/master/docs/tutorials/get-started.md

export GHUSER=molupini
> TODO: brew install fluxctl

fluxctl install \
--git-user=molupini \
--git-email=molupini@users.noreply.github.com \
--git-url=git@github.com:molupini/flux-get-started \
--git-path=namespaces,workloads \
--namespace=flux | kubectl apply -f -
