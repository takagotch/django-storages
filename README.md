### django-storages
---
https://github.com/jschneier/django-storages

```py
DEFAULT_FILE_STORAGE = 'storages.backends.s3boto3.S3Boto3Storage'

photo = models.FileField(
  storage=FileSystemStorage(location=settings.MEDIA_ROOT),
  upload_to='photos',
)

photo = models.FileField(
  upload_to='photos',
)
```

```sh
pip install django-storages
pip install -e 'git+https://github.com/jschneier/django-storages.git#egg=django-storages'
```

```
```


