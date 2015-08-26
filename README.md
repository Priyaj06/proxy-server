# proxy-server
Node js bootcamp


Run Server
bode index.js

verify it's running:
curl http://127.0.0.1:8000

Echo Server
curl -X POST http://127.0.0.1:8000 -d "hello self"

Proxy Server
curl -v http://127.0.0.1:8001/asdf -d "hello proxy"

