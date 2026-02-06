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
docker compose -f db.yamal up #monitoring
docker compose -f db.yamal up -d #backgroud
```

## Admin Interface (pgAdmin4)
Run the admin service:
```bash
docker compose -f admin.yaml up -d
```

## Application (Web Server)
Run the application service (Nginx):
```bash
docker compose -f app.yaml up -d
```