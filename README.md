# Envie ![Version](https://img.shields.io/badge/Version-0.0.1-green.svg)
====

Envie is a pure Go key/value store inspired by [Howard Chu's][hyc_symas]
[LMDB project][lmdb]. The goal of the project is to provide a simple,
fast, and reliable database for projects that don't require a full database
server such as Postgres or MySQL.

Since Envie is meant to be used as such a low-level piece of functionality,
simplicity is key. The API will be small and only focus on getting values
and setting values. That's it.

[hyc_symas]: https://twitter.com/hyc_symas
[lmdb]: http://symas.com/mdb/

## Project Status

Currently under development. Based on a fork of [Bolt][bolt] called [BBolt][forked]

[bolt]: https://github.com/boltdb/bolt
[forked]: https://github.com/etcd-io/bbolt

## Credits

Aditya Patil: [AdityaCyberSafe][adigit]
<br>
Bolt: [boltdb][boltgit]
<br>
etcd.io [etcd-io][etcdgit]

[adigit]: https://github.com/AdityaCyberSafe
[boltgit]: https://github.com/boltdb
[etcdgit]: https://github.com/etcd-io
