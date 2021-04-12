# Webpage

## Development

This tutorial will get you running a React web app from inside a container. Running code from inside a container, rather than just from your computer, will ensure that if the code works, then it will work anywhere (as long as it's running inside the same container). This won't change how you write code: you'll still be editing files some place on your computer. The only difference is where the code *runs*.

### Prerequisites

* Git
* Docker

This app comes with `create-react-app` source files. If you want to do this yourself (i.e. to use a later version), remove the `my-app` folder and create a new React app with:

```bash
$ rm -rf my-app
$ npx create-react-app my-app
```

### Instructions

1. Clone the repo onto your local computer. 

``` shell
$ git clone https://github.com/JayZ2398/webpage.git
```

2. `cd` into the project directory.

3. Build the container.

``` shell
$ docker-compose build
```

4. Run the container.

``` shell
$ docker-compose up
```

5. Wait a minute, and the shell should spit out some stuff including:

``` shell
react-ui    | You can now view app in the browser.
react-ui    |
react-ui    |   Local: http://localhost:3000
```

6. In your browser, open http://localhost:3000. You should see your running React app.
