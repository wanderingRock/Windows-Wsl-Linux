# Windows-Wsl-Linux

## wsl2 install & setting
參考文章: https://docs.docker.com/desktop/windows/wsl/

## wsl2 .wslconfig setting
參考文章:
1. https://learn.microsoft.com/en-us/windows/wsl/wsl-config#configure-global-options-with-wslconfig
2. https://learn.microsoft.com/en-us/windows/wsl/release-notes#build-18945
```
[wsl2]
kernel=<path>              # An absolute Windows path to a custom Linux kernel.
memory=<size>              # How much memory to assign to the WSL2 VM.
processors=<number>        # How many processors to assign to the WSL2 VM.
swap=<size>                # How much swap space to add to the WSL2 VM. 0 for no swap file.
swapFile=<path>            # An absolute Windows path to the swap vhd.
localhostForwarding=<bool> # Boolean specifying if ports bound to wildcard or localhost in the WSL2 VM should be connectable from the host via localhost:port (default true).

# <path> entries must be absolute Windows paths with escaped backslashes, for example C:\\Users\\Ben\\kernel
# <size> entries must be size followed by unit, for example 8GB or 512MB
```

## 

```


wsl -l

wsl -d Ubuntu //啟用

```

