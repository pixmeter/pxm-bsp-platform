# Build Context Configuration - LOCAL DEV

bare metal development build is integrated as follow:

* no docker container
* no publishing (manunally copy over packages or start qemu)
* sstate and download cache are at *../cache*
* ronto can be used

## External requirements:

* cache folder must be accessible and provide sufficient storage capacity
