# tcpdump-dckr

A docker image that runs tcpdump to capture traffic.

Based on an blog post from [jgamblin](https://github.com/jgamblin).

His orginal post can be found [here](http://jerrygamblin.com/2016/05/28/a-docker-container-to-capture-all-traffic-from-host/). 
 Have a read of his other posts too!


## Running

You can run this version with a similar command:

    docker run -v ~/pcap:/pcap --net=host -d mcrmonkey/tcpdump-dckr


you can run Jerry's original container with this command:

    docker run -v ~/pcap:/pcap --net=host -d jgamblin/tcpdump



## Building

If you like you can build your own version.

First, clone this repo to a location of your choosing on your own machine.

Then run the following in that directory:

    docker build -t tcpdump-dckr .


Then you should be all set


## License

I've not applied one.

You can do what ever you like to this version. However, I'd ask you link back here if you make something based on this.


