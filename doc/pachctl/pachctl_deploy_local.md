## ./pachctl deploy local

Deploy a single-node Pachyderm cluster with local metadata storage.

### Synopsis


Deploy a single-node Pachyderm cluster with local metadata storage.

```
./pachctl deploy local
```

### Options

```
  -d, --dev                Don't use a specific version of pachyderm/pachd.
      --host-path string   Location on the host machine where PFS metadata will be stored. (default "/var/pachyderm")
```

### Options inherited from parent commands

```
      --dry-run                       Don't actually deploy pachyderm to Kubernetes, instead just print the manifest.
      --no-metrics                    Don't report user metrics for this command
      --rethinkdb-cache-size string   Size of in-memory cache to use for Pachyderm's RethinkDB instance, e.g. "2G". Default is "768M". Size is specified in bytes, with allowed SI suffixes (M, K, G, Mi, Ki, Gi, etc) (default "768M")
  -s, --shards int                    The static number of shards for pfs. (default 32)
  -v, --verbose                       Output verbose logs
```

### SEE ALSO
* [./pachctl deploy](./pachctl_deploy.md)	 - Deploy a Pachyderm cluster.

###### Auto generated by spf13/cobra on 1-Dec-2016