# GOLANG GRAPHQL MONGODB CRUD Project

#### This is the accompanying code for my Youtube video with the same name (almost the same name)

##### Do the stuff below to initialize your project

1. Create a new folder for the Project
`mkdir gql-yt`
2. Mod init your project, give it whatever name you like
`go mod init github.com/akhil/gql-yt`
3. Get gql gen for your project
`go get github.com/99designs/gqlgen`
4. Add gqlgen to tools.go
`printf '// +build tools\npackage tools\nimport _ "github.com/99designs/gqlgen"' | gofmt > tools.go`
5. Get all the dependencies
`go mod tidy`
6. Initialize your project
`go run github.com/99designs/gqlgen init`