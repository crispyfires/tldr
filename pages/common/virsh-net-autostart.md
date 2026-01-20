# virsh net-autostart

> Enable or disable the automatic startup of a previously configured virtual network on libvirt daemon start.
> See also: `virsh`, `virsh-net-start`
> More information: <https://manned.org/virsh>.

- Enable the automatic startup of a virtual network on libvirt daemon start:

`virsh net-autostart {{network_name}}`

- Disable the automatic startup of a virtual network on libvirt daemon start:

`virsh net-autostart --disable {{network_name}}`
