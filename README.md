# securetoken

internal/
├── domain/
│   └── token.go
├── application/
│   └── token_service.go
├── infrastructure/
│   ├── redis_store.go
│   └── cookie_adapter.go
cmd/
└── service/
    └── main.go