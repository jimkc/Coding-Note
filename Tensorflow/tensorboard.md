## Use tensorbord with pytorch
Install <b>tensorboardx</b> at https://github.com/lanpa/tensorboardX.<br>

## Use tensor board to monitor from remote ip server
Opening default setting of tensorboard in current browser will only monitor local training process, 
so wee need to change settings while logging to remote server.<br>

```console
ssh -L 16006:127.0.0.1:6006 user@remote
```
Then, on your local machine (browser) simply open <br>
```console
http://127.0.0.1:16006/
```