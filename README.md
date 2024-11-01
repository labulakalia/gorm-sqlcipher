# GORM Sqlcipher Driver

![CI](https://github.com/go-gorm/sqlite/workflows/CI/badge.svg)

## USAGE

```go
import (
  "github.com/labulakalia/gorm-sqlcipher"
  "gorm.io/gorm"
)

// github.com/labulakalia/go-sqlcipher
db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
