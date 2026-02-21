# dfir-go-labs
## Download

[⬇ Download Windows Binary (ZIP)](https://github.com/redzeptech/dfir-go-labs/releases/latest/download/evtx-counter.zip)

> Unzip and run: `evtx-counter.exe -path "C:\Windows\System32\winevt\Logs" -top 10`
## Tools

### evtx-counter
Scan a folder for `.evtx` files, summarize total count/size, and list the largest logs.

**Run (Go):**
```bash
go run ./cmd/evtx-counter/main.go -path "C:\Windows\System32\winevt\Logs" -top 10


