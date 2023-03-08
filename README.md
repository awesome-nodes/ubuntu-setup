# ubuntu-setup
Collection of useful perfomance tunings for multi-gigabit and multi-core Linux Ubuntu system


### Configuration files
- [20-file-limits.conf](etc/sysctl.d/20-file-limits.conf)
- [20-kernel-options.conf](etc/sysctl.d/20-kernel-options.conf)
- [20-network-tuning.conf](etc/sysctl.d/20-network-tuning.conf)

Each file contains a detail description of parameters

### How to apply setting

Clone repository. Review content. Copy into system directory. Reload.

```bash
git clone https://github.com/awesome-nodes/ubuntu-setup.git
sudo cp etc/sysctl.d/20-* /etc/sysctl.d/
sudo sysctl --system
```