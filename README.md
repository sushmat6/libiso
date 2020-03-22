# A library of utilities related to payments, crypto, ISO8583 etc 

## UPDATE (03/22/2020)
1. There will be no further development on paysim, this repo will be strictly be used as a module/library
2. If you're interested in a ISO8583 simulator, please check out [isosim](https://github.com/rkbalgi/isosim)

## UPDATE (06/16/2019)
1. Folks developing on Windows please see this - https://github.com/rkbalgi/go/wiki/Building-on-Windows
2. Doesn't follow standard go style (coding conventions etc) - WIP
2. Not for production use - perhaps best suited for simulators


# Paysim
An open ISO8583 Simulator

<ul>
<li>The application is built using go and GTK+2 bindings made available at github.com/mattn/go-gtk (Thanks a ton Yashuhiro Matsumoto!)</li>
<li>The entire source code is available at https://github.com/rkbalgi/go</li>
<li>The interesting packages would be github.com/rkbalgi/go/execs/paysim, github.com/rkbalgi/go/paysim and github.com/rkbalgi/iso8583</li>
<li>There are loads of other interesting things available in other packages – like a minimalist implementation of a Thales HSM for basic commands (A6, MS, M6 and the like)
</li>
</ul>


# Some Screenshots
## The Main Application Screen
![](https://github.com/rkbalgi/github.io/blob/master/images_paysim/Paysim_MainScreen.png)
## Some Cryptographic Utilities (MAC'ing / PIN)
![](https://github.com/rkbalgi/github.io/blob/master/images_paysim/Paysim_Utils.png)
## After a response is received
![](https://github.com/rkbalgi/github.io/blob/master/images_paysim/Paysim_With_Response.png)

# A brief presentation
I have put together a brief presentation which is available here - https://docs.google.com/presentation/d/1UxxL4f_SO3NGpnx_N_v21RJoADOVK8YLrJYXRVnLw-4/edit?usp=sharing
