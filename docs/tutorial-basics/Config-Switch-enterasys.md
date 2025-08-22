---
sidebar_position: 2
---

# Config (Cấu hình VLAN)

  
###  Xóa port ra khỏi VLAN.  
```bash
config vlan vlanid <Tên_VLAN> delete <Tên_port>
``` 
###  Thêm port vào VLAN ở chế độ **untagged**.  
```bash
config vlan vlanid <Tên_VLAN> add untag <Tên_port>
```  
###  Cấu hình **PVID** (Port VLAN ID) cho port.  
```bash
config port_vlan <Tên_port> pvid <Tên_VLAN>
```  
###  Thêm port vào VLAN ở chế độ **tagged**.  
```bash
config vlan vlanid <Tên_VLAN> add tag <Tên_port>
```