# Apt mirror
In order to create your own local offline repository simply do the following.

* configure the repositories you want to mirror in the mirror.list file 

~~~
$ export APT_MIRROR_PATH=<The apt mirror path>
$ docker-compose -d
~~~
