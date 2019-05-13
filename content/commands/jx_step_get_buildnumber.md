---
date: 2019-05-12T06:57:56Z
title: "jx step get buildnumber"
slug: jx_step_get_buildnumber
url: /commands/jx_step_get_buildnumber/
---
## jx step get buildnumber

Outputs the current build number from environment variables or using the Downward API inside build pods

### Synopsis

Outputs the current build number from environment variables or using the Downward API inside build pods

```
jx step get buildnumber [flags]
```

### Examples

```
  # dislay the current build number
  jx step get buildnumber
```

### Options

```
  -h, --help   help for buildnumber
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

* [jx step get](/commands/jx_step_get/)	 - get [command]

###### Auto generated by spf13/cobra on 12-May-2019