# Jekyll example

An example Jekyll project that can be published to [Surge](https://surge.sh).

## Getting started

1. Install Surge and Jekyll:
  ```
  npm install
  # This will automatically run `bundle install` for Jekyll, too
  ```
2. Clone this repository, another Jekyll project, or just init a new one
3. Serve the project locally
  ```
  jekyll serve
  ```
4. Build the project locally
  ```
  jekyll build
  ```
5. Publish the project to Surge
  ```
  surge _site
  ```
  Alternatively, there’s an `npm run` script that will do 4. and 5. for you at once:

  ```
  npm run deploy
  ```  

## License

[The MIT License (MIT)](LICENSE.md)

Copyright © 2015 [Chloi Inc.](http://chloi.io)
