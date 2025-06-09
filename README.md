# 🏷️ ESPHome Keg Scale

This project adds a smart scale to your kegerator setup so you can estimate how much beer is left in your keg.  
Built using ESPHome and a load cell, this solution provides a simple, Wi-Fi connected way to monitor keg levels.

---

## 📶 Getting Started: Connecting Your Keg-a-Weigher Scale to Wi-Fi

Your scale ships with a built-in captive portal to make Wi-Fi setup easy.

---

### 🔌 Step 1: Power On the Scale

Plug the scale into a USB power source using the included cable.  
The device will boot up automatically.

---

### 📡 Step 2: Connect to the Setup Wi-Fi Network

On your phone, tablet, or computer:

1. Open your **Wi-Fi settings**
2. Connect to the network:  
   **`KegScaleWiFi`**
3. Enter the password:  
   **`MMMMBeer`**  _(four M’s, capital B)_

> ⚠️ This is a **temporary** network for setup only.

---

### 🌐 Step 3: Open the Captive Portal

After connecting:

- Most devices will automatically open the setup page
- If not, manually open a browser and go to:  
  **http://192.168.4.1**

You will see the **Keg-a-Weigher Wi-Fi Setup Page**

---

### 📲 Step 4: Enter Your Wi-Fi Credentials

1. Select your home/business Wi-Fi network
2. Enter your **Wi-Fi password**
3. Click **Save & Reboot**

The scale will reboot and attempt to connect to your Wi-Fi.

---

### ✅ Step 5: Verify Connection

- If successful, the **KegScaleWiFi** network will disappear and the device will join your Wi-Fi.
- If it fails, the device will return to **KegScaleWiFi** mode so you can try again.

---

## 🛠️ Troubleshooting

### ❌ I don’t see the `KegScaleWiFi` network

- Ensure the scale is powered on
- Move closer to the scale
- Reboot the device (unplug/plug in)

---

### ❌ The setup page didn’t open

- Open a browser and go to: **http://192.168.4.1**
- If that doesn’t work, forget the network and reconnect, or try a different device

---

### ❌ I entered the wrong Wi-Fi password

- The device will fail to connect and return to **KegScaleWiFi**
- Reconnect to the setup network and try again at **http://192.168.4.1**

---

### ❌ The scale keeps returning to setup mode

- Double-check the Wi-Fi password (case-sensitive)
- Make sure your router supports **2.4GHz** (not 5GHz only)
- Ensure the signal is strong near the scale
- Avoid using enterprise or login-protected Wi-Fi networks

---

## 🛠️ Initial Wi-Fi Setup

When your Keg Scale is first powered on, it creates a temporary Wi-Fi hotspot so you can connect it to your home network.

---

### 📶 Step 1: Connect to the Keg Scale’s Hotspot
1. Open Wi-Fi settings on your phone, tablet, or laptop.
2. Connect to the Wi-Fi network named:
   ```
   KegScaleWiFi
   ```
3. Enter the password:
   ```
   MMMMBeer
   ```

---

### 🌐 Step 2: Open the Configuration Page
Once connected, your device may automatically open a setup page.  
If not, open your browser and enter:
```
http://192.168.4.1/
```

---

### 🧭 Step 3: Select and Connect to Your Wi-Fi

You’ll see a list of available networks. It may look like this:

![Available Networks Screenshot](images/step3-networks.png)

> Note: Network names (SSIDs) shown will vary based on your location.

1. Tap the network you want to connect to.
2. Enter your **Wi-Fi password** in the box.
3. Tap the **Save** button.

You’ll see a message confirming the connection attempt:

![Connecting Message Screenshot](images/step3-connecting.png)

> *“The ESP will now try to connect to the network… Please give it some time to connect.”*

---

### 🔄 Step 4: Reconnect to Your Regular Wi-Fi

Once the Keg Scale attempts to join your selected Wi-Fi:
- Reconnect your phone or laptop to your usual home Wi-Fi network.
- The Keg Scale is no longer broadcasting its own Wi-Fi network.

---

### 🔍 Step 5: Find the Keg Scale on Your Network (Optional)

If needed, locate your device’s IP address using your router's connected devices list.

---

## ⚖️ First-Time Scale Calibration

Your Keg Scale is usually calibrated before shipping, but it may require recalibration after installation.

To calibrate the scale:

1. **Place the scale where it will be permanently installed.**
2. Go to the Keg Scale's web interface.
3. Under the **Calibrate** section, click **Set Zero Calibration**.  
   ![Step 3 - Set Zero Calibration](images/Step_3_Zero.png)

4. Place a known weight on the scale.
5. Enter the weight in the **Cal Point 1 Weight (lb)** field.  
   ![Step 5 - Cal Point 1 Weight](images/step5-cal1weight.png)

6. Wait about 5 seconds for the scale to stabilize.
7. Click **Set Cal Point 1**.  
   ![Step 7 - Set Cal Point 1](images/step7-cal1.png)

8. Replace the item with a **second, heavier known weight**.
9. Enter that weight into the **Cal Point 2 Weight (lb)** field.  
   ![Step 9 - Cal Point 2 Weight](images/step9-cal2weight.png)

10. Wait about 5 seconds again, then click **Set Cal Point 2**.  
    ![Step 10 - Set Cal Point 2](images/step10-cal2.png)

11. Once complete, the **Calibrated Weight** should show your accurate weight reading.  
    ![Step 11 - Calibrated Weight](images/step11-calibrated.png)


## 📎 Want to Help?

Contributions and ideas are welcome! Submit an issue or open a pull request.

---
