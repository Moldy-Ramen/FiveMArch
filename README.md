# FiveMArch
**Custom FiveM Arch server installation**

## VM Install Guide  
*If you already know how to install and launch a VM, you can skip this section.*

### Getting Started

#### Prerequisites  
You will need the following:  
1. **Arch ISO File**  
   - Download the Arch ISO file from the official Arch Linux website: [Arch Linux Download](https://archlinux.org/download/)  

2. **Virtual Machine Software**  
   - You can choose one of the following options for your virtual machine:
     - **VM Ware**: [Installation Guide](https://www.youtube.com/watch?v=PoNPBdKLZdk)  
     - **Hyper V**: [Installation Guide](https://www.youtube.com/watch?v=FCIA4YQHx9U)  
     - **Virtual Box**: [Installation Guide](https://www.youtube.com/watch?v=8mns5yqMfZk)

3. **VM Instance**  
   - Use one of the guides above to create a VM instance using the Arch Linux ISO.  
   - *Note: I skipped providing an instance creation guide due to the quality of the resources linked.*

---

### Arch Linux Installation  
1. **Set Keyboard Layout**  
   Run the following commands in your terminal:  
   ```bash
   sudo pacman -Syy
   sudo pacman -S archinstall
   archinstall
