# Laboratory

# Argilo

```
root@jessie:~$ git clone https://github.com/argilo/sdr-examples.git
Cloning into 'sdr-examples'...
remote: Counting objects: 202, done.
remote: Total 202 (delta 0), reused 0 (delta 0), pack-reused 202
Receiving objects: 100% (202/202), 1.42 MiB | 584.00 KiB/s, done.
Resolving deltas: 100% (116/116), done.
Checking connectivity... done.
root@jessie:~$  
```

```sh
root@jessie:~# cd sdr-examples/
root@jessie:~/sdr-examples# ls
ask_tx.grc	    COPYING	     multi_tx.grc     tutorial
atsc-b200.py	    dvb-freq-fix.py  multi_tx.py      va3odg.grc
atsc-blade.py	    dvbt-b200.py     multi_tx.wav     va3odg.py
atsc-blade-usb2.py  dvbt-blade.py    ntsc	      va3rft.grc
atsc-hackrf.py	    dvbt-hackrf.py   pager_rx_929.py  va3rft.py
ceiling_fan_rx.grc  dvbt-tx.py	     pager_rx.py      wspr_hackrf.grc
ceiling_fan_tx.grc  gfsk_tx.grc      README.rst
```

```sh
root@jessie:~/sdr-examples# python pager_rx.py 
linux; GNU C++ version 4.9.1; Boost_105500; UHD_003.007.003-0-unknown

Using Volk machine: ssse3_32_orc
gr-osmosdr 0.1.3 (0.1.3) gnuradio 3.7.5
built-in source types: file osmosdr fcd rtl rtl_tcp uhd miri hackrf bladerf rfspace airspy 
Using device #0 Realtek RTL2838UHIDIR SN: 00000001
Found Rafael Micro R820T tuner
```

# Multimode

- [Multimode receiver for Gnu Radio](https://github.com/patchvonbraun/multimode)