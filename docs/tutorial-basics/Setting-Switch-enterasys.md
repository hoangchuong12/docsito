---
sidebar_position: 3
---

# Cấu hình VLAN cho port 8

Dưới đây là ví dụ cấu hình nhiều VLAN trên **port 8**.

---

### VLAN quản lý thiết bị (`manage_device`, tag 10)
```bash
create vlan manage_device tag 10
config vlan manage_device add untagged 8 advertisement disable
config port_vlan 8 pvid 10
