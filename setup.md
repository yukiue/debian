## keybinding(caps→ctrl)
    $ emacs /etc/default/keyboard

    XKBOPTIONS="ctrl:nocaps"

## wireless-networks
    $ sudo emacs /etc/wpa_supplicant/wpa_supplicant.conf
    
    network={
        ssid=""
        psk=""
    }
    
    $ sudo emacs /etc/network/interfaces
    
    auto wlp2s0
    iface wlp2s0 inet dhcp
    wpa-conf /etc/wpa_supplicant/wpa_supplicant.conf

## sudo
    # visudo
    
    hoge  ALL=(ALL:ALL) ALL

## mozc


## mathematica

[install for linux](http://support.wolfram.com/kb/12453)
    
[activate](https://reference.wolfram.com/language/tutorial/ActivatingMathematica.html)