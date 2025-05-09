# README

only once

```sh
./lr setup
```

## up

add a domain name (such as https://react.localhost redirecting to http://localhost:3000)

```sh
./lr up react 3000
```

## down

tear down an alias

```sh
./lr down react
```

## FAQ

Q: it's not working from the shell!
A: yup, only the browsers support the domain .localhost; you could add a line in /etc/hosts corresponding to your hostname

Q: it's not working from the browser!
A: did you restart the browser after executing the `./lr setup` command?

Q: I am getting a 502
A: check that your service is actually running on that port
