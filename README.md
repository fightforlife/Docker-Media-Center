# Docker Media Center
 personal Setup to use my Server as a Media Center


pacakges that need to be installed on the host

vainfo libxv1 va-driver-all vdpau-driver-all xtermin xinit xserver-xorg-video-intel xserver-xorg-input-all vainfo libxv1 intel-media-va-driver-non-free libva-drm2 libva-x11-2

Needed for xorg intel HW accel

sudo mkdir -p /etc/X11/xorg.conf.d
cd /etc/X11/xorg.conf.d/
sudo ln -s /usr/share/doc/xserver-xorg-video-intel/xorg.conf 10-intel.conf