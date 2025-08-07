# Linkding

The bookmark manager Linkding.

## Post-installation

No users are installed from the start, so you need to add one with this command.
Find the linkding container name with `docker ps`.

```bash
docker exec -it <container name> python manage.py createsuperuser --username=joe --email=joe@example.com
```

