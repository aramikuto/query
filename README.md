TODO:
- (possibly that will require map/set changes):
  - making a map where we'd store all fetcher store arguments (keys, store, settings),
  and a singular set that requires refetching due _to any reasons_. Run all fetchers
  from there each time
  - add document.focus event handler
  - add blur + reconnect event handler + interval
- mutator

ideas for future:
1. steal some ideas from here: https://swr.vercel.app/docs/api#options
2. events (global and isolated to a single store)
