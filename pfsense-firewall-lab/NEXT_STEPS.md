# Phase 2 checklist

- [ ] Confirm available disk space and memory on host
- [ ] Download a lightweight Linux ISO from its official source
- [ ] Create client VM and attach its NIC to Internal Network `SOC-LAB`
- [ ] Boot client and verify DHCP address in 192.168.1.100–199
- [ ] Test ping to 192.168.1.1 and internet/DNS separately
- [ ] Open pfSense web GUI at https://192.168.1.1 from the client
- [ ] Change default password and document configuration (no secrets)
- [ ] Test one allow rule and one deny rule; save logs and observations
