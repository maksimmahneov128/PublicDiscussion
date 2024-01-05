# PublicDiscussion

____
clone branch "git clone https://github.com/maksimmahneov128/PublicDiscussion.git -b main"

```
docker compose up --build 
```

```
docker compose up -d
```

```
docker compose exec web python manage.py collectstatic 
```

```
docker compose exec web python manage.py migrate --noinput 
```

```
docker compose exec web python manage.py createsuperuser 
```
