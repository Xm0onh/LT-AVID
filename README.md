# LT-AVID
Asynchronous verifiable information dispersal with libp2p in golang

Manual running:
```go
go run . -node=Node<ID>
```

Automatic running:
```bash
./StartNodes.sh
```

Stop the all the nodes:
```terminal
ps aux | grep go | grep -v grep | awk '{print $2}' | xargs kill -9
```