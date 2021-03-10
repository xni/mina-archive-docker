Docker-образ Mina+Archive
=========================

Как собрать
-----------

На машине, где будет собираться образ, необходимо выполнить:

```
git clone https://github.com/xni/mina-archive-docker && \
cd mina-archive-docker && \
git clone https://github.com/jrwashburn/mina-pool-payout && \
docker build -t nikitin/mina-archive-bp:1.0.2 .
```

Затем, работаем как с обычным образом minaprotocol/mina-daemon-baked:1.0.2-06f3c5c.
