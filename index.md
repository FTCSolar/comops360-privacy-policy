# Privacy Policy — ComOps360 Commissioning App (Android)

**Effective date:** 08-06-2026
**Last updated:** 08-06-2026

This Privacy Policy explains how the **ComOps360 Commissioning App** ("the App," "we,"
"us," or "our"), provided by **FTC Solar, Inc.** ("FTC Solar"), handles information when you
use it to commission and configure solar tracker equipment in the field.

The App is a **professional field tool** intended for authorized technicians and installers.
It is used to set up and configure solar site equipment — Zone Controllers, Row Controllers,
sensors, and related network settings. It is **not** a consumer or social application and is
**not directed to children**.

> **Scope of this policy.** This policy describes the operational and equipment data the App
> exchanges with FTC Solar's servers through its commissioning data interface ("CX Data").
> Sign‑in/authentication is handled separately by your organization's identity provider and
> is outside the scope of this document.

---

## 1. Summary (Google Play Data Safety at a glance)

- The App **does not collect personal or sensitive user data** such as your name, email
  address, phone number, contacts, photos, or your personal device location.
- The App **does not use your phone's GPS** to track you. Any latitude/longitude it processes
  is the **geographic location of the solar site/equipment**, entered as configuration data.
- The data the App handles is **technical equipment and site‑configuration data** that you
  enter or that is provisioned for a project.
- This data is **transmitted to FTC Solar's servers** to perform commissioning. It is **not
  sold**, and **not shared** with third parties for advertising or marketing.
- The App **does not include advertising** and **does not use third‑party analytics or
  tracking SDKs** for advertising purposes.

---

## 2. Information the App Handles

The App sends and retrieves the following **operational/equipment data** through the CX Data
interface. This information relates to **solar sites and hardware**, not to individuals:

### 2.1 Site & Solar‑Tracking Configuration
- Site name and site location label (e.g. city/state text).
- Site **geographic coordinates (latitude, longitude) and timezone**, used by the Solar
  Position Algorithm to position solar trackers.

> These coordinates identify the **solar installation**, not the user. They are entered as
> project/site configuration, not derived from your device's location services.

### 2.2 Zone & Network Configuration
- Zone names and inverter identifiers.
- Equipment network settings: static IP address, gateway, subnet, and inter‑controller
  (Zone Controller to Zone Controller) IP addresses.
- Wireless mesh settings (XBee/Zigbee): PAN ID, channel, and device counts.
- Time‑synchronization settings (e.g. GPS time sync) and terminal/board settings.

### 2.3 Equipment Identifiers & Commissioning Status
- Row Controller and device **identifiers** (device IDs), **hardware serial numbers**, row/
  tracker IDs, and commissioning status.

### 2.4 Control Commands
- Configuration commands and parameter values sent to controllers (for example, stow angles
  and other tracker settings).

The App may store the above **locally on the device** as needed to function in the field
(including offline), and synchronizes it with FTC Solar's servers when connectivity is
available.

---

## 3. Information the App Does NOT Collect

Through the CX Data interface, the App does **not** collect or process:

- Personal identifiers (name, email, phone number, government IDs).
- Your personal/device location (GPS), or background location.
- Contacts, calendar, SMS/call logs, microphone, or photos/media for personal use.
- Advertising identifiers or cross‑app tracking data.
- Health, financial, or other sensitive personal data.

---

## 4. How the Information Is Used

The information is used solely to:

- Provision, commission, and configure solar site equipment.
- Discover, validate, and associate controllers and devices during commissioning.
- Apply site‑specific and tracker settings (e.g. stow configuration) to controllers.
- Synchronize commissioning results with FTC Solar's ComOps360 platform for record‑keeping
  and ongoing operations of the solar site.

We use the data only for these operational purposes — **not** for advertising, profiling, or
sale.

---

## 5. Device Permissions

The App requests the following Android permissions strictly to perform commissioning:

- **Internet / Network access** — to exchange commissioning data with FTC Solar's servers.
- **Bluetooth / Nearby devices** — to connect to and configure controllers and sensors over
  Bluetooth during commissioning.
- **Location** — on some Android versions, the operating system requires location permission
  to perform **Bluetooth scanning for nearby equipment**. It is used **only** for discovering
  commissioning hardware and is **not** used to determine, store, or share your personal
  location.

You can manage permissions at any time in your device settings; revoking required permissions
may prevent the App from functioning.

---

## 6. Data Sharing & Disclosure

- The data is transmitted to and stored by **FTC Solar** (and its hosting/cloud
  infrastructure providers acting on our behalf) to operate the ComOps360 platform.
- We **do not sell** your data and **do not share** it with third parties for advertising.
- We may disclose information if required by law, regulation, legal process, or to protect
  the rights, safety, and security of FTC Solar, our customers, or the public.

---

## 7. Data Security

We use reasonable technical and organizational measures to protect data, including encrypted
transport (HTTPS/TLS) between the App and our servers and access controls on our systems. No
method of transmission or storage is completely secure, but we work to protect information
consistent with industry practices.

---

## 8. Data Retention

Commissioning and configuration records are retained for as long as needed to operate and
maintain the associated solar site and to meet our legal, contractual, and operational
obligations. Locally cached data on the device can be cleared by clearing the App's storage
or uninstalling the App.

---

## 9. Data Deletion Requests

Because commissioning data belongs to the solar site/project operated through your
organization, requests to access or delete project data are handled through your organization
and FTC Solar. To make a request, contact us using the details in **Section 12**.

---

## 10. Children's Privacy

The App is a professional tool intended for authorized technicians and is **not directed to
children under 13** (or the equivalent minimum age in your jurisdiction). We do not knowingly
collect personal information from children.

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. Material changes will be reflected by
updating the "Last updated" date above and, where appropriate, through the App or other
communication. Continued use of the App after changes take effect constitutes acceptance of
the updated policy.

---

