---
date: 2019-05-16T14:02:26Z
title: "jx start pipeline"
slug: jx_start_pipeline
url: /commands/jx_start_pipeline/
---
## jx start pipeline

Starts one or more pipelines

### Synopsis

Starts the pipeline build.

```
jx start pipeline [flags]
```

### Examples

```
  # Start a pipeline
  jx start pipeline foo
  
  # Select the pipeline to start
  jx start pipeline
  
  # Select the pipeline to start and tail the log
  jx start pipeline -t
```

### Options

```
  -m, --custom                Use a custom Jenkins App instead of the default execution engine in Jenkins X
  -f, --filter string         Filters all the available jobs by those that contain the given text
  -h, --help                  help for pipeline
  -j, --jenkins-name string   The name of the custom Jenkins App if you don't wish to use the default execution engine in Jenkins X
  -t, --tail                  Tails the build log to the current terminal
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

* [jx start](/commands/jx_start/)	 - Starts a process such as a pipeline

###### Auto generated by spf13/cobra on 16-May-2019