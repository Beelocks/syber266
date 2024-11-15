
# Updated Exploit Project

## Setup

1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

2. Jalankan exploit dengan opsi CLI:
   ```sh
   python src/exploit.py --target-ip 192.168.1.100 --target-port 443 [--usb-vendor-id 0x1234 --usb- 
   product-id 0x5678]
   ```


   **Options:**
   - `--target-ip`: IP address of the target.
   - `--target-port`: Port of the target.
   - `--usb-vendor-id: (Optional) USB Vendor ID of the device to manipulate.
   - `--usb-product-id: (Optional) USB Product ID of the device to manipulate.
   
3. Finding Encryption Key
   ```sh
   python3 src/exploit.py --target-ip 192.168.1.100 --target-port 443
