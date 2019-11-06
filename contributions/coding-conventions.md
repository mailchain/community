# Code Conventions

## Go

* [Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)
* [Effective Go](https://golang.org/doc/effective_go.html)
* Know and avoid [Go landmines](https://gist.github.com/lavalamp/4bd23295a9f32706a48f)

* Comment your code.
  * [Go's commenting conventions](http://blog.golang.org/godoc-documenting-go-code)
  * If reviewers ask questions about why the code is the way it is, that's a sign that comments might be helpful.
* Command-line flags should use dashes, not underscores

* Naming
  * Please consider package name when selecting an interface name, and avoid redundancy. e.g.: `storage.Interface` is better than `storage.StorageInterface`.
  * These articles will explain how to organize your Go packages:
    * <https://rakyll.org/style-packages/>
    * <https://medium.com/@benbjohnson/standard-package-layout-7cdbc8391fc1#.ds38va3pp>
    * <https://peter.bourgon.org/go-best-practices-2016/#repository-structure>
    * [Design philosophy for packages](https://www.goinggo.net/2017/02/design-philosophy-on-packaging.html)
  * Do not use uppercase characters, underscores, or dashes in package names.
    * Please consider parent directory name when choosing a package name.
    * protocols/ethereum/foo.go should say `package ethereum` not `package protocolsethereum`.
    * Unless there's a good reason, the `package ethereum` line should match the name of the directory in which the .go file exists.
    * Importers can use a different name if they need to disambiguate.
    * Properties or functions that return an objects type should use the word `kind` or `Kind`.

* Locks
  * Locks should be called `lock` and should never be embedded (always `lock sync.Mutex`).
  * When multiple locks are present, give each lock a distinct name following Go conventions - `stateLock`, `mapLock` etc.
