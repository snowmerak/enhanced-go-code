# Enhanced Go Code

## Business Logic

### Process

#### Context

`WithDeadline`, `WithTimeout`, `WithCancel`, `signal.WithNotify`, `context.AfterFunc`

#### Profile

`pprof`, `trace`, `pgo`

#### Test

`testing`

#### Timeout

`http.Client`, `http.Server`, `context.WithTimeout`, `time.After`

### Allocate

#### Lazy Init

`sync.Once`, `Sync.OnceFunc`, `sync.OneValue`, `sync.OnceValues`, `sync.OnceDo`

#### Map & Set

`shrink`, `struct{}`

#### Make with size

#### Max Process

`runtime.GOMAXPROCS`

#### Goroutine Pool

`ants`

#### Object Pool

`sync.Pool`

#### Write Buffer

`strings.Buffer`, `bytes.Buffer`, `strings.Builder`

#### Read Scanner

`scanner`, `bufio`

#### Copy & Append

`copy`, `append`

### Concurrency

#### Channel

`chan`, `for range`, `select`, `consume`

#### Mutex

#### Map

`sync.Map`

#### Semaphore

`go.org/x/sync/semaphore`, `waitgroup`, `go.org/x/sync/errgroup`

#### Atomic

`sync/atomic`, `ownership`

#### Singleflight

`go.org/x/sync/singleflight`

## Data Structure

### Data Serialization

#### JSON

`json`, `json-iterator/go`, `fastjson`

#### Protobuf

#### FlatBuffers