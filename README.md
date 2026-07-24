# Yi-Shou (Ian) Lee

Linux OS Engineer at Lenovo Infrastructure Solutions Group, working on enterprise server bring-up, RHEL enablement, platform validation, and hardware-software integration.

## Enterprise Linux and Server Platforms

- Lenovo ThinkSystem server integration across CPU, memory, storage, NIC, power, UEFI, XCC/BMC, POST, and OS boot
- RHEL validation across boot health, power management, TPM, RAS, NVMe/RAID, SR-IOV, virtualization, and accelerator subsystems
- KVM/QEMU/libvirt validation, including AMD SME, SEV, and SEV-ES
- Linux RAS memory validation using ACPI EINJ, MCA handling, PFA page retirement, and memory mirroring
- Platform defect reproduction, kernel and system-log analysis, and repeatable evidence collection
- Test procedures, scripts, execution trackers, and validation notes for cross-team engineering work

## FPGA and Hardware-Software Integration

- AX7015B / Zynq-7015 board bring-up and system integration
- Restored stable 1 Gbps RGMII Ethernet reception using Vivado ILA, IDDR, and IDELAYE2 debugging
- Integrated Xilinx XDMA PCIe Gen2 with Zynq PS DDR3 for host-to-card and card-to-host transfers
- Patched the Linux XDMA driver for a custom PCIe device ID and restored working `/dev/xdma*` interfaces
- Automated FPGA build, board programming, PS initialization, packet testing, and ILA capture using Tcl, Make, XSCT, Python, and Scapy
- Validated sustained PCIe DMA throughput above 800 MB/s
- Measured packet-processing and AXI-Lite latency in hardware

## Tools and Technologies

**Operating systems:** Linux, RHEL, Embedded Linux  
**Virtualization:** KVM, QEMU, libvirt  
**Programming:** C, C++, Python, Bash, Tcl  
**Build and automation:** Make, Git, XSCT  
**FPGA:** AMD/Xilinx Zynq-7000, Vivado, Xsim, ILA, VIO  
**Interfaces and subsystems:** PCIe, XDMA, Ethernet, RGMII, AXI4, AXI4-Lite, DDR, NVMe, SR-IOV, RAS
