```bash
$ watch -n 300 ./do-smth.sh # do smth every 300 sec
$ ps -ax | grep -i do-smth.sh # to find process
$ kill <PID> # to kill process
```

# nohup
```bash
$ nohup watch -n 3 ./do-smth.sh & # to keep process if terminal closed
$ exit
```
