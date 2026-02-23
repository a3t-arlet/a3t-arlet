# Workflows

These are outcome-oriented examples of how Karuna is used.

## Debug a realtime UI bug
- Trace the event path end-to-end (backend → bridge → frontend)
- Add lightweight instrumentation to confirm the failure mode
- Produce a minimal patch and a clear rollback plan

## Validate and harden a Go SDK
- Run `go test ./...`, `go test -race ./...`, and `go vet ./...`
- Add targeted tests around edge cases and concurrency
- Provide a coverage snapshot and a prioritized test plan

## PR review (security + correctness)
- Identify risk areas (auth, parsing, persistence, crypto, concurrency)
- Call out footguns (missing timeouts, unbounded goroutines, silent drops)
- Suggest minimal improvements and add tests where it matters
