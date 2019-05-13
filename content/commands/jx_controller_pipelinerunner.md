---
date: 2019-05-12T06:57:56Z
title: "jx controller pipelinerunner"
slug: jx_controller_pipelinerunner
url: /commands/jx_controller_pipelinerunner/
---
## jx controller pipelinerunner

Runs the service to generate Tekton PipelineRun resources from source code webhooks such as from Prow

### Synopsis

Runs the service to generate Tekton PipelineRun resources from source code webhooks such as from Prow

```
jx controller pipelinerunner [flags]
```

### Examples

```
  # run the pipeline runner controller
  jx controller pipelinerunner
```

### Options

```
      --bind string              The interface address to bind to (by default, will listen on all interfaces/addresses).
  -h, --help                     help for pipelinerunner
      --no-git-init              Disables checking we have setup git credentials on startup
  -p, --path string              The path to listen on for requests to trigger a pipeline run. (default "/")
      --port int                 The TCP port to listen on. (default 8080)
      --service-account string   The Kubernetes ServiceAccount to use to run the pipeline (default "tekton-bot")
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

* [jx controller](/commands/jx_controller/)	 - Runs a controller

###### Auto generated by spf13/cobra on 12-May-2019