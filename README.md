# Usage

- **go get**

```shell
go get github.com/keepchen/JudgeServerClient
```

- **go mod**

```shell
go mod download github.com/keepchen/JudgeServerClient
```

```golang
import judge "github.com/keepchen/JudgeServerClient"

...

client := judge.NewClient(judge.WithTimeout(0))
client.SetOptions(judge.WithEndpointURL("http://127.0.0.1:12358"), judge.WithToken("MY-TOKEN-STRING"))
```

# Oirgin

[QingdaoU/JudgeServer](https://github.com/QingdaoU/JudgeServer)
