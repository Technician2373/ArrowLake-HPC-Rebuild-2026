# Btrfs Layout & Snapshot Strategy

This document describes the isolated partition layout used for Arrow Lake HPC development, including:

- Dedicated Btrfs partition
- Ubuntu /root + /home combo partition
- Snapshot strategy
- Subvolume layout
- Why this layout works well for kernel development
- How snapshots protect against bad kernel boots
