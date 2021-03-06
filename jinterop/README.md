# stompngo_examples - Java JMS Interoperability #

## Supported Brokers ##

* ActiveMQ
* Artemis

## Assumptions ##

* ActiveMQ Message Broker
* Openwire / TCP port at 61616
* STOMP port at 61613

or:

* Artemis Message Broker
* Artemis / TCP port at 31616
* STOMP port at 31613

## Java and go Preparation ##

* Modify cp.sh to provide your AMQ lib location
* Run ./compile.sh

## Send and Receive With go ##

* Run ./gosend.sh
* Run ./gorecv.sh

## Send and Receive With Java ##

* Run ./jsend.sh
* Run ./jrecv.sh

## Send With go and Receive With Java ##

* Run ./gosend.sh
* Run ./jrecv.sh

## Send With Java and Receive With go ##

* Run ./jsend.sh
* Run ./gorecv.sh

## Cleanup After Testing ##

* Run ./clean.sh

## Miscellaneous ##

One can send and receive using Java of course, or send and receive using go.

