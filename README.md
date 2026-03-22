# ShrotiHost WhatsApp Manager for WHMCS

![WHMCS](https://img.shields.io/badge/WHMCS-Latest-blue)
![PHP](https://img.shields.io/badge/PHP-8.1%20%7C%208.2%20%7C%208.3-purple)
![IonCube](https://img.shields.io/badge/IonCube-v14+-orange)
![License](https://img.shields.io/badge/License-Commercial-success)

A powerful **WHMCS WhatsApp automation module** built for hosting providers who want to send professional WhatsApp notifications directly from WHMCS.

**ShrotiHost WhatsApp Manager** connects WHMCS with **Washroti** and helps you automate invoice alerts, payment confirmations, ticket updates, service notifications, phone verification OTPs, admin alerts, and bulk campaigns from one place.

It includes a modern admin dashboard, queue controls, merge-field based templates, PDF invoice delivery, and mobile-friendly management tools for daily operations.

---

# ✨ Key Features

- Automated WhatsApp notifications for WHMCS email events
- Function-based WhatsApp alerts for important admin and client actions
- Bulk WhatsApp campaigns with filtering, scheduling, and queue control
- PDF invoice sending with real WHMCS invoice PDF support
- Phone verification OTP system for WHMCS clients
- Merge-field based template system with WhatsApp-friendly formatting
- Admin dashboard with message statistics and status insights
- Logs, queue management, and campaign tracking
- License-protected commercial module
- Responsive admin interface for desktop and mobile

---

# 🚀 What This Module Can Handle

- Invoice created, reminders, overdue notices, payment confirmations, refunds
- Support ticket opened, replied, feedback request, auto-close notices
- Service provisioning, suspension, unsuspension, termination, welcome flows
- Admin login alerts, client login alerts, password change alerts
- Manual WhatsApp sends from the admin/client context
- Client export to Washroti-compatible CSV
- OTP-based phone number verification
- Bulk messaging to filtered or imported recipients

---

# 📸 Screenshots

## Info Dashboard

![Info Dashboard](screenshots/info-dashboard.png)

## Message Logs & Queue

![Logs and Queue](screenshots/logs-and-queue.png)

## Phone Verification Overview

![Phone Verification Clients](screenshots/phone-verification-clients.png)

## Phone Verification OTP Settings

![Phone Verification OTP Settings](screenshots/phone-verification-otp-settings.png)

## Bulk Queue Manager

![Bulk Queue Manager](screenshots/bulk-queue-manager.png)

## Campaign Details

![Campaign Details](screenshots/campaign-details.png)

## Bulk Send Builder

![Bulk Send Builder](screenshots/bulk-send-builder.png)

## Client Export

![Client Export](screenshots/client-export.png)

## Email Template Library

![Email Template Library](screenshots/email-templates-library.png)

## Function Templates

![Function Templates](screenshots/function-templates.png)

## Bulk Message Templates

![Bulk Message Templates](screenshots/bulk-message-templates.png)

## Module Settings

![Settings Page](screenshots/settings-page.png)

---

# ⚙ Requirements

- **WHMCS Latest Version**
- **PHP 8.1 / 8.2 / 8.3**
- **IonCube Loader v14+**
- MySQL/MariaDB with **utf8mb4** support for emoji-safe template storage
- Active **commercial license key**
- Valid **Washroti** account credentials

For proper emoji support in WHMCS, add this line to your `configuration.php`:

```php
$mysql_charset = 'utf8mb4';
```

---

# 📦 Installation & Setup

1. Upload the module to:

```text
/modules/addons/shrotihost_whatsapp/
```

2. Make sure these directories are writable by the web server:

```text
/modules/addons/shrotihost_whatsapp/storage
/modules/addons/shrotihost_whatsapp/templates_c
/modules/addons/shrotihost_whatsapp/uploads
/modules/addons/shrotihost_whatsapp/hooks/pdf_output
```

3. In WHMCS Admin, go to:

```text
System Settings → Addon Modules
```

4. Activate **ShrotiHost WhatsApp Manager**

5. Open the module and go to **Settings**

6. Sign in to your Washroti account and prepare your credentials:

- Main website: https://washroti.in
- Subscription / plan management: https://washroti.in/user/subscription

7. Enter:

- **License Key**
- **App Key**
- **Auth Key**
- **Washroti Email**
- Optional **Admin Support WhatsApp Number**

8. Save settings and start configuring templates, automation, and verification flows

---

# 🧩 Main Module Areas

## Info

Track message activity with:

- Last 24 hours dashboard
- Weekly and monthly insights
- Status mix and trend charts
- Trigger/campaign breakdown
- Queue snapshot
- Washroti account sync panel

## Logs & Queue

Monitor every message with:

- Send status
- Queue state
- Filters
- Requeue actions
- Manual send now action

## Phone Verification

Manage:

- Verified clients
- Unverified clients
- Pending OTP verifications
- OTP settings and template

## Bulk Send

Create campaigns using:

- Client filters
- Manual recipients
- CSV import
- Bulk templates
- Delay and scheduling controls

## Templates & Automation

Includes:

- Email-based templates
- Function-based templates
- Bulk message templates
- Merge field support
- Import tools for default templates

---

# 🪄 Merge Field Support

The module supports rich merge fields across:

- Client details
- Invoice details
- Service/product details
- Support ticket details
- Domain details
- Useful WHMCS URLs

This allows you to build larger WhatsApp templates with:

- Emojis
- Dynamic invoice links
- Ticket links
- Service details
- Payment method names
- PDF invoice delivery

---

# 🔒 Licensing

This module is a **commercial product** and requires an active **License Key**.

Without an active license:

- restricted module tabs remain locked
- protected messaging features remain unavailable
- module activation is incomplete until licensing is configured

License activation is done directly from the **Settings** tab inside the module.

---

# 📱 Mobile Friendly

The admin interface is designed to work on:

- Desktop
- Tablet
- Mobile devices

Wide sections such as tabs, tables, logs, and queues are optimized for smaller screens to remain manageable inside WHMCS admin.

---

# 🔗 Buy / Product Link

**ShrotiHost WhatsApp Manager**

https://portal.shrotihost.in/index.php/store/whatsapp-notification/shrotihost-whatsapp-manager-whmcs

---

# 🤝 Support

If you need installation help, licensing help, or customization support, contact **ShrotiHost**.

Website: https://shrotihost.in

---

# 🌐 Author

Made with ❤️ by **ShrotiHost**
