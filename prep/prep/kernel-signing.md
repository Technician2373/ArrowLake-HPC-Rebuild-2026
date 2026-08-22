# Kernel Signing & Secure Boot Workflow

This document contains the exact steps used to sign mainline kernels, enroll MOK keys, replace unsigned kernels, and maintain Secure Boot compatibility on Ubuntu 26.04.

Sections to fill:
- Generating MOK keys
- Enrolling keys via shim/MOK manager
- Signing vmlinuz with sbsign
- Replacing unsigned kernels
- update-grub workflow
- Verifying signatures
- Troubleshooting shim/MOK failures
