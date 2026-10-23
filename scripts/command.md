curl -X POST https://<image-api>.<your-subdomain>.workers.dev \
 -H "Authorization: Bearer your-secret-api-key" \
 -H "Content-Type: application/json" \
 -d '{"prompt": "A cute robot cooking breakfast"}' \
 --output image.jpg

curl.exe -X POST "https://image-api.owen-sharp.workers.dev" -H "Authorization: Keepah11!" -H "Content-Type: application/json" -d '{"prompt":"A cute robot cooking breakfast"}' --output image.jpg

curl.exe -sS -w "`nHTTP Status: %{http_code}`n" -X POST "https://image-api.owen-sharp.workers.dev" -H "Authorization: Bearer Keepah11!" -H "Content-Type: application/json" -d '{"prompt":"A cute robot cooking breakfast"}' -o image.jpg

curl.exe -sS -X POST "https://image-api.owen-sharp.workers.dev" -H "Authorization: Bearer Keepah11!" -H "Content-Type: application/json" -d '{"prompt":"A cute robot cooking breakfast"}'

curl.exe -sS -w "`nHTTP Status: %{http_code}`n" -X POST "https://image-api.owen-sharp.workers.dev" -H "Authorization: Bearer Keepah11!" -H "Content-Type: application/json" -d '{"prompt":"A cute robot cooking breakfast"}' -o image.png
