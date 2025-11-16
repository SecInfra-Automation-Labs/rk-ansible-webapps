# rk-ansible-webapps

This repo. is used to create a simple node.js app on the appserver without mysql database.
The appserver is created using Vagrant from ansible_chap2 (another project).

The app.js is added manually afterwards and tested from the ansible control node
using curl http://192.168.56.5:3000.

This project also contains sample mysql configuration for future use (this is in fact
used in the next repo : rk-nodjs-app.)
