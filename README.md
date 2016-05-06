# senna-img-bug

Reproduces a weird bug with senna and images.

## Setup

1. Install NodeJS >= [v0.12.0](http://nodejs.org/dist/v0.12.0/), if you don't have it yet.

2. Install local dependencies:

  ```
  npm install
  ```

3. Run the server:

  ```
  npm run server
  ```

4. Open the example using the url the previous command indicated (something
  like **localhost:8080**). The example accessible via `<url>/` works
  as expected, while `<url>/demos/senna/` doesn't. Just load the example and
  you'll see that the image fails to be fetched.
