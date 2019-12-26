# Created with reference to Docker best practice

## IMages
- Debian9
- php7.3
- MySQL8.0
- nginx
- busybox

## Usage
### Copy .env from .env.example
cp .env.example .env

### Write project file name
APP_CODE_PATH_HOST=../portfolio

### Execution docker-compose
docker-compose up -d

### Setting application database host
kankan-mysql or 172.20.0.20
