# Atom Kubernetes Snippets

An Atom snippet library for Kubernetes. [Language-yaml](https://atom.io/packages/language-yaml) must be installed.

## Install

Go to Packages > Settings View > Open once in settings go to the Install tab and search for k8-snippets

Restart Atom

## Development

```sh
$ cd ~/.atom/packages
$ git clone https://github.com/starlightromero/k8-snippets.git
$ cd k8-snippets $ apm install $ apm link
```

## Snippets

the → means the TAB key

Trigger                  | Content
:----------------------- | :-------------------------------------------------------------------------------------------------------------------------------
`ConfigMap→`             | set configuration data separately from application code
`Deployment→`            | declarative updates for Pods and ReplicaSets
`Ingress→`               | manages external access to the services in a cluster
`LoadBalancer→`          | externally-accessible IP address that sends traffic to the correct port on your cluster nodes
`NodePort→`              | NodePort Service
`PersistentVolume→`      | a piece of storage in the cluster that has been provisioned by an administrator or dynamically provisioned using Storage Classes
`PersistentVolumeClaim→` | a user's request for and claim to a persistent volume
`Pod→`                   | a group of one or more containers, with shared storage and network resources, and a specification for how to run the containers
`ReplicaSet→`            | import react and useEffect
`ReplicationController→` | import react, useState and useEffect
`Secret→`                | store and manage sensitive information
`Service→`               | abstract way to expose an application running on a set of Pods as a network service
`StorageClass→`          | a way for administrators to describe the "classes" of storage they offer

## Contributing

1. Fork it!
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -m 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request

## License

MIT License © Starlight Romero

## Credit

This package was forked from [haddadnidal](https://github.com/haddadnidal/Kubernetes-snippet) and expanded.
