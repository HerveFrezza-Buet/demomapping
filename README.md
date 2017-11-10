# demomapping

This repository gathers unmaintained source for the sake of compiling my VQ 3D demo.

For compiling one source, let say the package xxxx do

```
tar zxvf xxxx.tar.gz
cd xxxx
mkdir build
cd build
cmake .. -DCMAKE_INSTALL_PREFIX=/usr
sudo make install
cd ../..
```

# Install

```
sudo apt install libgl1-mesa-dev libgl1-mesa-dev libglu1-mesa libglu1-mesa-dev libgtk2.0-0 libgtk2.0-dev libgtkglext1 libgtkglext1-dev

```

an then install the following packages, in that order.
<ul>
<li>glop</li>
<li>glop-gtk</li>
<li>mapdist</li>
<li>vq2</li>
<li>demo_mapping</li>
</ul>

# Run

```
demomapping-demo 
```