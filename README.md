# markdown-tool

## init project
### init cmd
```
go get github.com/spf13/cobra/cobra
cobra init github.com/dormael/markdown-tool --pkg-name github.com/dormael/markdown-tool
```

### init dep
```
cd github.com/dormael/markdown-tool
go get -u github.com/golang/dep/cmd/dep
dep init
```

### add command
```
cobra add version
cobra add follow
```

## build
```
go build -o mdt && mv mdt ~/bin/
```