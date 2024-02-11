# GraphQL

```
 ~ go mod init GraphQL

 ~ printf '// +build tools\npackage tools\nimport (_ "github.com/99designs/gqlgen"\n _ "github.com/99designs/gqlgen/graphql/introspection")' | gofmt > tools.go\n

 ~ go run github.com/99designs/gqlgen init

# run graphQL
 ~ go run ./server.go

```
