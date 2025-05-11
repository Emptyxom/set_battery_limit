# set_battery_limit 
🔋 **Battery Charge Limiter for Linux**  
*A simple yet powerful tool to extend your laptop battery lifespan by setting custom charge thresholds (e.g., 80%).*

---

### **Features** ✨  
✅ **Custom Thresholds**: Set any limit between 1-100% via CLI.  
✅ **Auto-Detection**: Works with `BAT0`, `BAT1`, or other battery interfaces.  
✅ **Systemd Integration**: Runs automatically at startup.  
✅ **Error Handling**: Validates inputs and detects unsupported hardware.  
✅ **One-Click Uninstall**: Clean removal script included.  

---

### **Quick Start** 🚀  
```bash
git clone https://github.com/YOUR_USERNAME/battery-charge-limit.git  
cd battery-charge-limit/src  
sudo ./install.sh 80  # Set to 80% (default)  
