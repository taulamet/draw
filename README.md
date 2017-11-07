![alt text](https://f.cloud.github.com/assets/220864/730169/feb98294-e24b-11e2-903d-b3cbc68f3a48.gif "Action Video")

## An intuitive collaborative drawing web based tool.
Collaborative real-time drawing, sketching & painting

Fast, light weight, easy to maintain.  Try the [demo](http://draw.etherpad.org).

Demo
----
[Etherdraw Demo site](http://draw.etherpad.org)

Installation
------------

On Debian Jessie.

```bash
# Install Requirements
sudo apt-get update && sudo apt-get install git libcairo2-dev libjpeg62-turbo-dev libpango1.0-dev libgif-dev build-essential g++
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash - && sudo apt-get install -y nodejs
git clone git://github.com/JohnMcLear/draw.git
cd draw
bin/run.sh 
```

Make a drawing! Open your browser and visit `` http://127.0.0.1:9002 ``

Requirements
------------
 * [NodeJS](http://nodejs.org/)
 * Lib Cairo
 * Lib Jpeg
 * Lib Gif

License
-------
Apache 2 License

Donations
---------
Donate to the [Etherpad Foundation](http://etherpad.org/#links)
