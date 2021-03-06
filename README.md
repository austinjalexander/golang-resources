# golang-resources

✅ https://go.googlesource.com/

✅ https://github.com/golang/go

✅ https://github.com/golang/go/wiki

### Blogs
- https://dave.cheney.net/2011/02
- https://www.goinggo.net/2013/05/why-go-programming.html
- https://blog.golang.org/go-whats-new-in-march-2010
- https://medium.com/@benbjohnson
- [package visualization](https://anvaka.github.io/pm/#/galaxy/gosearch?cx=0&cy=0&cz=0&lx=0.0000&ly=0.0000&lz=0.0000&lw=1.0000&ml=150&s=1.75&l=1&v=2017-11-30T09-00-00Z)

### Branding
- https://blog.golang.org/go-brand

### Community
- https://invite.slack.golangbridge.org/
- https://groups.google.com/forum/#!forum/golang-nuts
- https://groups.google.com/forum/#!forum/golang-codereviews
- https://go-store.io/

### Contributing
- https://golang.org/doc/contribute.html
- [How to Contribute to Go](https://golang.org/s/gophercon2017) (slides from Community Day, GopherCon 2017; [direct link](https://docs.google.com/presentation/d/1ap2fycBSgoo-jCswhK9lqgCIFroE1pYpsXC1ffYBCq4/edit#slide=id.p))
- https://godoc.org/golang.org/x/review/git-codereview
- https://help.github.com/articles/closing-issues-using-keywords/
- https://github.com/golang/go/issues
- https://go-review.googlesource.com
- https://github.com/golang/go/wiki/ExperienceReports

### Database
- http://go-database-sql.org/index.html
- https://www.alexedwards.net/blog/using-postgresql-jsonb

### Dependency Management
- https://github.com/golang/go/wiki/Modules#quick-start
- https://sdboyer.io/dep-status/
#### Go modules

#### Init

```shell
go mod init
```

Tools: https://github.com/go-modules-by-example/index/blob/master/010_tools/README.md

##### Makefile

```shell
.PHONY: all clean install

all:
	go mod vendor
	go build -mod=vendor ./...

clean:
	go mod tidy

install: all
	go install -mod=vendor ./...

```
- https://www.kablamo.com.au/blog-1/2018/12/10/just-tell-me-how-to-use-go-modules

### Design
- https://dave.cheney.net/2016/08/20/solid-go-design
- https://peter.bourgon.org/go-for-industrial-programming/
- https://medium.com/@benbjohnson/standard-package-layout-7cdbc8391fc1
- https://the-zen-of-go.netlify.com/

### Documentation
```go
godoc regexp | grep -i parse
```

### Generics
- https://github.com/golang/proposal/blob/master/design/15292-generics.md
- [Summary of Go Generics Discussions](https://docs.google.com/document/d/1vrAy9gMpMoS3uaVphB32uVXX4pi-HnNjkMEgyAHX4N4/edit#)
- https://pbs.twimg.com/media/DEjApdzXcAAlhH7.jpg
- http://jmoiron.net/blog/notes-on-the-go2-generics-draft/
- https://emilymaier.net/words/getting-specific-about-generics/

### History
- https://commandcenter.blogspot.com/2012/06/less-is-exponentially-more.html

### Humor
- https://github.com/SuperPaintman/the-evolution-of-a-go-programmer

### IoT
- https://tinygo.org/

### Learning
- https://github.com/ardanlabs/gotraining/tree/master/topics/courses/go
- https://github.com/enocom/gopher-reading-list
- https://go101.org/article/101.html

### Layout
- https://github.com/golang-standards/project-layout

### Performance
- https://github.com/dgryski/go-perfbook

### Research Papers
- https://github.com/golang/go/wiki/ResearchPapers

### Security
- https://www.gitbook.com/book/checkmarx/go-scp/details
- https://github.com/securego/gosec
- https://github.com/OWASP/Go-SCP

### SSL/TLS
- https://github.com/mholt/certmagic

### Style
- http://go-proverbs.github.io/

### Testing
- https://talks.golang.org/2014/testing.slide#1
- https://speakerdeck.com/mitchellh/advanced-testing-with-go
- https://medium.com/@povilasve/go-advanced-tips-tricks-a872503ac859
- https://medium.com/@harrygogonis/testing-go-mocking-third-party-dependancies-4ab4e1c9bd3f

## To Investigate

### Code Evaluation
- https://github.com/golang/example/tree/master/gotypes

### Complexity
- https://github.com/fzipp/gocyclo

### Data
- https://github.com/gonum/gonum
- https://github.com/kniren/gota

### Dev Tools
- https://github.com/codegangsta/gin

### Design Patterns
- https://github.com/tmrts/go-patterns
- http://www.golangpatterns.info/

### Documentation
- https://github.com/adams-sarah/test2doc
- https://github.com/fluhus/godoc-tricks

### Errors
- https://blog.golang.org/errors-are-values

### Frameworks
- https://gobuffalo.io

### Hardware
- https://periph.io/

### Image Processing
- https://primitive.lol/

### Learning
- https://learn-anything.xyz/programming/programming-languages/go
- https://github.com/jbuberel/go-patterns
- https://github.com/manyminds/api2go
- https://golangbot.com/learn-golang-series/
- https://github.com/teh-cmc/go-internals
- https://quii.gitbook.io/learn-go-with-tests

### Logging
- https://github.com/sirupsen/logrus

### Mocking
- https://github.com/golang/mock
- https://github.com/sourcegraph/gen-mocks
- https://github.com/vektra/mockery
- https://github.com/DATA-DOG/go-sqlmock

### Presenting
- https://godoc.org/golang.org/x/tools/present

### Profiling
- https://www.reddit.com/r/golang/comments/8neprv/theres_no_pprof_documentation/?st=JHU0L4FP&sh=9a94c42c

### Projects
- https://github.com/avelino/awesome-go
- https://github.com/micro/go-micro
- https://github.com/micro/micro

### Robots!
- https://gobot.io/

### Testing
- http://goconvey.co/

### Tooling
- https://www.alexedwards.net/blog/an-overview-of-go-tooling

### Verification
- [Formal verification of concurrency in go](http://ieeexplore.ieee.org/document/7748882/)
