Title: Bhyve, The BSD Hypervisor bag.1
Date: 2016-03-28 20:30
Modified: 2017-04-09 23:40
Tags: virtualisasi, bhyve, freebsd, qemu, virtual-box, xen, hypervisor, jail, docker
Category: FreeBSD
Slug: mengenal-install-dan-konfigurasi-bhyve-the-bsd-hypervisor-bag1
Authors: andy.zs
Summary: Take a look at bhyve the BSD Hypervisor. Mengenal, menginstall dan konfigurasi Bhyve hypervisor dari FreeBSD projek.


Bhyve adalah *hypervisor* dari komunitas FreeBSD . Jika linux memiliki kernel based *virtualization* yang kita kenal sebagai `KVM` maka `bhyve` bisa kita katakan sebagai `KVM`nya dari  FreeBSD ini. Bhyve ini tergolong teknologi baru untuk dukungan dan stabilitasnya sendiri tentu masih dibawah `KVM` apalagi `VMware` dan `XenServer`, tapi meskipun demikian `bhyve` sudah didukung libvirt untuk mempermudah pengontrolan dan manejemennya.

Pada tutorial ini kita akan membahas tutorial menggunakan bhyve sebagai virtualisasi, bhyve sendiri sudah dibawa secara default di FreeBSD 10.0-RELEASE, untuk menggunakannya kita hanya tinggal meload module nya saja.





