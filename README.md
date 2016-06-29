# logspout-logstash-docker

A logspout docker image with Logstash & UDP adapters baked in.

This image builds on two things (Thanks a ton to Gliderlabs and Looplab based on whose work this image is built)

* Uses the https://github.com/gliderlabs/logspout/tree/master/custom to build a custom image for Logsprout with Logstash module built in
* Uses Logstash adapter from https://github.com/looplab/logspout-logstash
