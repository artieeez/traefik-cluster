kubectl run curl-debug --image=curlimages/curl -it --rm --restart=Never -- sh

# Test App A
curl http://whoami