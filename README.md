# getsignal

Get a [signal](https://golang.org/pkg/syscall/#Signal) from its name.

```
import "github.com/jsoriano/getsignal"
```
```
signalName := "SIGUSR1"
signal, err := getsignal.FromName(signalName)
```
