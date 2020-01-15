# Running Fathom on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ys/fathom-on-heroku)

- check that everything is working

```bash
heroku run bin/fathom --version
```

- add the first user

```bash
heroku run bin/fathom user add --email="test@test.com" --password="test_password"
```

- open the browser to login and add your first website

```bash
heroku open
```

- ENJOY :)
