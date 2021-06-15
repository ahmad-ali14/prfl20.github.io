# NEW PAGE

| ERROR |  SOLUTION |
| :-: | :-: |
| Fatal error: Allowed memory size of 2097152 bytes exhausted (tried to allocate 65536 bytes) | insert this `ini_set('memory_limit', '-1');` before the line causing the issue  |
