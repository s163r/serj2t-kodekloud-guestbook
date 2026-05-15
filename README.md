# serj2t-kodekloud-guestbook


```
k expose deployment redis-master --port=6379 --name=redis-master
k expose deployment redis-slave --port=6379 --name=redis-slave
k expose deployment frontend --type=NodePort --name=frontend
```
change noteport
