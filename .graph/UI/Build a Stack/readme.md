# "Build a Compute Stack"
Build this Frontend in Flutter & Django! It will be Fun. :-)
- uses 

The Backend is controlled entirely by OpenStack, Kubernetes, Container APIs! As a final option we allow "Libvirt" & Virt-Manager and our toolstack for fully custom builds.
- hypervisor: Xen, KVM
- container: 

## UI & workflow
You Select a Hardware, OS, Environment, & Software combinations as a "Unit" it looks like this!
- multiple stacked layers
- these are Composable! Each can be changed out
- made ofrectangular "bricks"
- each layer can be "Favorited", pinned, stored, and searched for later


# Example:
```
____________________________________
|            Hardware              |
|-SSD-|-ARM64-|-DynamicMem-|-10gbe-|
|__________________________________|
|           Hypervisor             |
|       KVM: nested, hugepages     |
|__________________________________|
|             Graphics             |
|---Discrete: NVIDIA Tesla, OVMF---|
|__________________________________|
|           Environment            |
|---------OS: Ubuntu 23.04---------|
|------Env: Gnome Shell & KDE------|
|__________________________________|
|            Libraries             |
|--Unity, Unreal, Tensor, OpenCV---|
|__________________________________|
|               Apps               |
|-Chrome, VSCode, Pycharm, Kraken- |
|__________________________________|
|        UniStor Filesystem        |
| Ceph(local)| Backblaze | Perkeep |
____________________________________
```
