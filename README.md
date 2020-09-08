# OpenShift-PoC
Also using this repo for recording important commands and notes related to each chapter of DO288 course.

Playground setup for OpenShift PoC


Download oc cli for MacOS from https://mirror.openshift.com/pub/openshift-v3/clients/3.10.0-0.69.0/macosx/
Note -> download version 3.10.0. Later version may not work
unzip oc.tar

#move oc executable file to user path
mv oc /usr/local/bin

brew install socat

oc cluster up

The server is accessible via web console at:
    https://127.0.0.1:8443

You are logged in as:
    User:     developer
    Password: <any value>

To login as administrator:
    oc login -u system:admin

brew update

brew install --HEAD xhyve

brew cask install minishift

minishift start
