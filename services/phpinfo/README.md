# Simple PHP Info Page

## Build Image

    docker build -t wamoco/phpinfo .

## Deploy

Change this to your domain.

    export DOMAIN=yourdomain.example.com;

Deploy service

    envsubst < deploy.yaml | kubectl apply -f -
