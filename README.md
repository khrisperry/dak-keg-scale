# ESPHome Keg Scale

This project was create to add a scale for kegs so you know how much beer is remaining in the keg (at least an estimate).  

📶 Connecting Your Keg-a-Weigher Scale to Wi-Fi
Your Keg-a-Weigher scale ships preconfigured with a built-in captive portal to help you easily connect it to your home or business Wi-Fi network.

🔌 Step 1: Power On the Scale
Plug the scale into a USB power source using the included cable. The device will boot up automatically.



📡 Step 2: Connect to the Setup Wi-Fi Network
On your phone, tablet, or computer:

Open your Wi-Fi settings.

Look for a network named:
KegScaleWiFi

Connect using this password:
MMMMBeer (four M’s, capital B)

⚠️ This is a temporary Wi-Fi network used for setup only.



🌐 Step 3: Open the Captive Portal
After connecting:

Most devices will automatically open the configuration page.

If it doesn’t, manually open a browser and go to:
http://192.168.4.1

You’ll now see the Keg-a-Weigher Wi-Fi Setup Page.



📲 Step 4: Enter Your Wi-Fi Credentials
Select your Wi-Fi network from the list.

Enter your Wi-Fi password.

Click Save & Reboot.

The scale will reboot and attempt to connect to the Wi-Fi network you selected.



✅ Step 5: Verify Connection
If successful, the KegScaleWiFi network will disappear, and the scale will operate normally.

If it fails to connect, it will return to KegScaleWiFi mode so you can try again.

🛠️ Troubleshooting
❌ I don’t see the KegScaleWiFi network
Make sure the scale is powered on.

Move closer to the scale to ensure better signal.

Try rebooting the device by unplugging and plugging it back in.

❌ The setup page didn’t open automatically
Open a browser manually and go to: http://192.168.4.1

If that doesn't work, forget the network and reconnect, or try a different device.

❌ I entered the wrong Wi-Fi password
The scale will fail to connect and automatically fall back to KegScaleWiFi mode.

Reconnect to KegScaleWiFi and re-enter the correct credentials at http://192.168.4.1.

❌ The scale keeps returning to setup mode
Double-check your Wi-Fi credentials (case-sensitive).

Make sure your router isn't using 5GHz only (ESP devices support 2.4GHz Wi-Fi only).

Ensure your Wi-Fi signal is strong near the scale’s location.

Avoid using enterprise Wi-Fi or networks that require extra login steps.
