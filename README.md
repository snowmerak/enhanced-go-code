# enhanced-go-code

## Process

### Context

`WithDeadline`, `WithTimeout`, `WithCancel`, `signal.WithNotify`, `context.AfterFunc`

### Profile

`pprof`, `trace`, `pgo`

### Test

`testing`

## Allocate

### Map & Set

`shrink`, `struct{}`

### Make with size

### Max Process

`runtime.GOMAXPROCS`

### Goroutine Pool

`ants`

### Object Pool

`sync.Pool`

### Write Buffer

`strings.Buffer`, `bytes.Buffer`, `strings.Builder`

### Read Scanner

`scanner`, `bufio`

## Concurrency

### Channel

`chan`, `for range`, `select`, `consume`

### Mutex

### Map

`sync.Map`

### Semaphore

`go.org/x/sync/semaphore`, `waitgroup`, `go.org/x/sync/errgroup`

### Atomic

`sync/atomic`, `ownership`

### Singleflight

`go.org/x/sync/singleflight`

## Data Serialization

### JSON

`json`, `json-iterator/go`, `fastjson`

### Protobuf

### FlatBuffers