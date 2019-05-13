---
date: 2019-05-12T06:57:56Z
title: "jx step post install"
slug: jx_step_post_install
url: /commands/jx_step_post_install/
---
## jx step post install

Runs any post install actions

### Synopsis

This pipeline step ensures that all the necessary jobs are imported and the webhooks set up - e.g. for the current Environments. 

It is designed to work with GitOps based development environments where the permanent Environments like Staging and Production are defined in a git repository. This step is used to ensure that all the 'Environment' resources have their associated CI+CD jobs setup in Jenkins or Prow with the necessary webhooks in place.

```
jx step post install [flags]
```

### Examples

```
  jx step post install
```

### Options

```
      --env-job-credentials string   The Jenkins credentials used by the GitOps Job for this environment
  -h, --help                         help for install
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx step post](/commands/jx_step_post/)	 - post step actions

###### Auto generated by spf13/cobra on 12-May-2019