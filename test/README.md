# Test

```sh
cd docker-pdf-form-fill-server
curl \
  -H "Content-Type: application/json" \
  -X POST --data "@test/data.json" \
  -k https://<docker host ip>:<docker container host port>/ \
  > test.pdf \
  && open test.pdf
```
