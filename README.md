出典: https://github.com/overleaf/overleaf/tree/main

使い方: docker-compose.yml をダウンロードし、`docker compose up --remove-orphans` で起動。http://localhost:8080/launchpad に接続。

公開方法: `docker run --net=host cloudflare/cloudflared tunnel run --url http://localhost:8080` とすると一時的に他人と共有できる
