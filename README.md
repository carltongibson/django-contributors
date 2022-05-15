

To update data run `github-to-sqlite`. Then commit and push: 

```shell
$ github-to-sqlite commits data/django-commits.db django/django
$ git add data/django-commits.db
$ today=$( date '+%Y-%m-%d')
$ git commit -m "Updated commits to: ${today}"
$ git push
```