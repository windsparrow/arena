## arena top job

Display Resource (GPU) usage of jobs.

### Synopsis

Display Resource (GPU) usage of jobs.

```
arena top job [flags]
```

### Options

```
      --allNamespaces     show all the namespaces
  -h, --help              help for job
  -i, --instance string   Display instance top info
  -r, --refresh           Display continuously
```

### Options inherited from parent commands

```
      --arena-namespace string   The namespace of arena system service, like tf-operator (default "arena-system")
      --config string            Path to a kube config. Only required if out-of-cluster
      --loglevel string          Set the logging level. One of: debug|info|warn|error (default "info")
  -n, --namespace string         the namespace of the job (default "default")
      --pprof                    enable cpu profile
      --trace                    enable trace
```

### SEE ALSO

* [arena top](arena_top.md)	 - Display Resource (GPU) usage.

###### Auto generated by spf13/cobra on 24-Apr-2019
