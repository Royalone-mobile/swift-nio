# Changes in the Public API from NIO 1 to NIO 2

- removed all previously deprecated functions, types and modules.
- made `EventLoopGroup.makeIterator()` a required method
- `TimeAmount.Value` is now `Int64` (from `Int` on 64 bit platforms, no change
  for 32 bit platforms)

