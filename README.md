# Install balena-etcher to ubuntu 22.04
 I documented a problem using balenaEtcher-1.7.9-x64.AppImage on unbutu 22.04 here.

24 Nov 2022

I'm having problems using .AppImages in ubuntu 22.04 so I'm looking for a solution. and i found that its problem is FUSE problem with ubuntu 22.04. but don't worry just follow my example you will be able to use it.

Install FUSE

~~~
sudo apt install libfuse2
~~~

Download file from `https://www.balena.io/etcher/` then

~~~
cd Downloads/

sudo ./balenaEtcher-1.7.9-x64.AppImage
~~~

Oh!! It finally worked
