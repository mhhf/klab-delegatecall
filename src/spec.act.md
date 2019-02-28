```
behaviour delegate of Caller
interface delegate()

types

  CALLEE      : address Callee

storage

  0 |-> CALLEE

storage CALLEE

  0 |-> 0

iff

  VCallDepth < 1024
  VCallValue == 0

```
