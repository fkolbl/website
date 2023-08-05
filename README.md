# website

F. Kolbl professional website - built with Jekyll. 

## local dev
starting from nothing, clone the git repository with:
```
git clone https://github.com/fkolbl/website.git
```

Website modification and implementation can be performed locally. Docker should be installed. Once in the website folder just type the command:
```
docker-compose up
```

the website can be accessed in a browser at the address [http://0.0.0.0:4000/index.html](http://0.0.0.0:4000/index.html)

## deploy
deployement is automatized with a github action, nothing to do but adding file, ceating a commit and pushing with:
```
git add -A
git commit -m "my message"
git push
```
and it will be online after few minutes, as an action is triggered on push on main branch (see /.github/workflows/deploy.yml).
