# freeswitch-modules

## mod_ali_tts 基于阿里云语音合成模块

```
uuid_broadcast 52011b87-9ff0-4c7e-8d02-d58390e02711 speak::ali_tts|aixia|'hello world'
```

## mod_ali_asr 基于阿里云语音识别模块

```
telnet 127.0.0.1 8021

auth ClueCon

```

- 开启语音识别

```
sendmsg 5047289e-03a8-4cd0-92b2-532b6c1b5a4d
call-command: execute
execute-app-name: start_asr
```

- 关闭语音识别

```
sendmsg 5047289e-03a8-4cd0-92b2-532b6c1b5a4d
call-command: execute
execute-app-name: stop_asr
```
