## Description

[Tarantool](https://github.com/tarantool/tarantool) snapshot reader.

## Usage

```python

import tarantool_snapshot

count = 0
for space_id, tuple_data in tarantool_snapshot.iter("/snaps/00000000010388786179.snap"):
  count += 1

print count

```
