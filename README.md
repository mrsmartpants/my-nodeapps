# Node Apps
## my-nodeapps

## ONLINE DEMO

  <http://myapps.nodejitsu.com/>

![](https://github.com/nodeapps/my-nodeapps/raw/master/screenshots/my-nodeapps.png)

# Requirements

- Active nodejitsu account

# Installation

    mkdir myapp
    cd myapp/
    jitsu install my-nodeapps

*If you do not have `jitsu` installed you can install it via `npm install jitsu -g`*


# Configuration

In order to run the `my-nodeapps` application, you will need to modify the `config.json` with your nodejitsu credentials.


```js
{
  "username": "marak",
  "password": "password"
}
```

# Usage

### Starting locally

    node bin/server

*Now you can visit http://localhost:8080 to view your node apps*

### Deploy to nodejitsu

    jitsu deploy

*You will now be prompted for a `subdomain` to deploy your application on*


# License

(The MIT License)

Copyright (c) 2011 Nodejitsu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
