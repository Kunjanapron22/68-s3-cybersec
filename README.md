# Cyber Security


## Owner
 - 6702041511152
 - Kunjanapron Kaewtubtim
 - s6702041511152@email.kmutnb.ac.th


 
## Environment
```sh
cp env.simple .env
```


## Running services
### Database
```sh
docker compose -f db.yaml up #monitoring
docker compose -f db.yaml up -d #backgroud
```


## Admin Interface (pgAdmin4)
Run the admin service:
```bash
docker compose -f admin.yaml up -d
```


## Application (Web Server)
Run the application service :
```bash
docker compose -f app.yaml up -d
```

