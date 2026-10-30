# Privacy Policy for VoluGuard

**Effective Date:** October 30, 2026  
**Last Updated:** October 30, 2026  

VoluGuard ("we", "our", or "the App") is developed by Prashant Sugara. This Privacy Policy describes how your information is handled when you use the VoluGuard Android application.

---

### 1. Zero Personal Data Collection
VoluGuard is built with privacy as a foundational principle. **We do not collect, store, transmit, sell, or share any personal information or identifiable user data.**

- **No Account Required:** You do not need to create an account, register, or provide your email or personal credentials to use the App.
- **No Analytics or Trackers:** The App does not contain third-party tracking libraries, behavioral analytics (like Firebase Analytics or Mixpanel), or advertising SDKs.
- **No Internet Transmission of Device Data:** All volume configuration, safe limits, Bluetooth MAC associations, and logs remain strictly local to your device.

---

### 2. Device Permissions and How They Are Used
To provide automatic Bluetooth volume management and safe listening enforcement, VoluGuard requests the minimum necessary Android system permissions:

- **Bluetooth (`BLUETOOTH_CONNECT`, `BLUETOOTH_SCAN`):**  
  Used solely to detect when your paired Bluetooth audio devices (car stereos, earbuds, headphones, speakers) connect or disconnect, and to identify their device names and MAC addresses so your custom volume profiles can be applied automatically.
- **Modify Audio Settings (`MODIFY_AUDIO_SETTINGS`):**  
  Used to set, adjust, and clamp media volume according to your chosen safe limits and target volumes.
- **Notification Policy (`ACCESS_NOTIFICATION_POLICY` - Optional):**  
  Used exclusively if you choose to enable the optional "Do Not Disturb" feature while connected to a specific device (e.g., while driving).
- **Foreground Service (`FOREGROUND_SERVICE_MEDIA_PLAYBACK`):**  
  Used to temporarily process volume enforcement handshakes and settle delays when Bluetooth accessories connect without being terminated by the operating system.

None of the data accessed via these permissions is ever transmitted off your device.

---

### 3. In-App Purchases (Google Play Billing)
If you choose to upgrade to VoluGuard Pro, transactions are processed directly by Google via the Google Play Billing Library. We do not have access to, nor do we store, your credit card number, bank details, or billing address. Google Play manages payment processing in accordance with the [Google Play Privacy Policy](https://policies.google.com/privacy).

---

### 4. Children’s Privacy
VoluGuard does not knowingly collect or solicit any personal information from children under the age of 13.

---

### 5. Open and Transparent
The App operates entirely offline with respect to user data and configurations. You may reset or erase all saved device profiles and history at any time by clearing the App's storage in your Android system settings or uninstalling the App.

---

### 6. Changes to This Privacy Policy
If we update this Privacy Policy, the revised version will be posted on this page with an updated "Last Updated" date.

---

### 7. Contact Us
If you have questions or concerns regarding this Privacy Policy, please contact us at:  
**Email:** prashantsugara@gmail.com  
**Developer:** Prashant Sugara  
**GitHub:** [https://github.com/prashantsugara/VoluGuard](https://github.com/prashantsugara/VoluGuard)
