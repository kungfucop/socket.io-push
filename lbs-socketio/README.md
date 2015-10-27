###install nodejs

```
sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install npm
sudo npm install -g n
sudo n stable
```

###install socket.io

```
npm install socket.io
npm install socket.io-redis
```

###run

node .

###push api

http://183.61.6.33/api/push?pushId=abc&data=aGVsbG93IHdvcmxk&topic=/topic/test&pushAll=true

data -> base64 encoded byte array

topic -> client subscribed topic

pushId -> generated by client

pushAll -> push to all clients subscribing topic