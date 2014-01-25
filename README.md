# TweetBeat or The Legend of Moltar
by Daniel Earthy, Tyler Olson, Daniel Kimbel, Marc Cordier

## Overview
Starting with a simple idea of "hearing twitter data" we created a drum/sample machine in javascript that can interface with the Twitter Streaming API. 

The drum machine nicknamed "Moltar" listens for tweets containing keywords and when one of those keywords is found it triggers the sample that it has been assigned to.

##Technology Used

**JS Web Audio API** - The audio engine and sample library manager of the drum machine.  Used to create XY filter pad and volume control as well as real-time switchable sample libraries.

**Jquery** - Interface as well as for the draggable twitter keyword listeners

**Rails 4** - Hosted our App and provided streaming support for the Twitter Streaming API through the server to the client.

**Puma** - HTTP Server that supports Rails 4 streaming

**Twitter Streaming API**  - Allowed us to listen and filter hundreds of thousands of tweets per minute. 
