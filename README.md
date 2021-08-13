# nba-player_heights

A function that searches through NBA Player heights database based on user input, and match the all pairs of players whose height in inches adds up to the integer input.

## Install me

```bash
npm init
npm i axios
npm install -D typescript
npm i -D @types/node @types/express
tsc --init
```

## Excecute me

```bash
tsc index.ts
node index
```

## Resources

[Use nodemon and ts-node](https://www.youtube.com/watch?v=zRo2tvQpus8)

**version 0.0.0**

## Axios

Axios used to retrieve data from the [endpoint](https://mach-eight.uc.r.appspot.com/).

Axios has url in request object. Fetch has no url in request object. Axios is a stand-alone third party package that can be easily installed. Fetch is built into most modern browsers; no installation is required as such. And request package has been deprecated.

## Demo code

```bash
# compile
tsc index.ts
# excecute
node index.js 139
- Brevin Knight         Nate Robinson
- Mike Wilks            Nate Robinson
```

## Things to master

* [x] sort the players data
* [X] refactor using interfaces
* [X] implement a more efficient algorithm
* [X] handle repeated data (handling array size)

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
1. Clone your Fork
1. Navigate to your local repository
1. Create your Feature Branch

```bash
git checkout -b nba-player_heights/masterFeature
```

3. Commit your Changes

```bash
git commit -m 'Add some masterFeature')
```

4. Push to the Branch

```bash
git push origin nba-player_heights/masterFeature
```

5. Open a Pull Request

## Contributors

- Alejandro Franco Cedeño: <afrancocedeno@gmail.com> |
  [Github](https://github.com/afrancocedeno) |
  [Twitter](twitter.com/afrancocedeno) |
  [Linkedin](linkedin.com/in/afrancocedeno/)

## License & Copyright

© Alejandro Franco Cedeño, SWE.
