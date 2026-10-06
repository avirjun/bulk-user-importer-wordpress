# 📥 Bulk User Importer for WordPress

A lightweight and easy-to-use **WordPress plugin for importing multiple users in bulk from a CSV file**.

Save time when migrating users, creating accounts, or managing large user databases. The plugin allows administrators to upload a CSV file and create WordPress users automatically with usernames, emails, passwords, roles, and other user information.

---

## ✨ Features

* 📂 Import multiple WordPress users from a CSV file
* 👤 Create users automatically in WordPress
* 🔐 Support for passwords
* 🛡️ Assign WordPress user roles
* 📧 Import usernames and email addresses
* 📊 Process large user lists efficiently
* ⚡ Simple and beginner-friendly interface
* ✅ Validate required user information
* ⚠️ Detect duplicate usernames and emails
* 🔄 Useful for migrations and bulk account creation

---

## 🎯 Use Cases

This plugin can be useful for:

* Migrating users from another website
* Creating hundreds or thousands of WordPress accounts
* Importing users from an existing database
* Membership websites
* Educational platforms
* Community websites
* Employee or internal portals
* WooCommerce customer migration
* Bulk account creation

---

## 📄 CSV Format

Prepare your CSV file with the required user information.

### Example

```csv
username,email,password,role,first_name,last_name
john,john@example.com,Password123!,subscriber,John,Doe
jane,jane@example.com,Password456!,subscriber,Jane,Smith
adminuser,admin@example.com,Password789!,editor,Admin,User
```

### Supported Fields

| Field        | Description         |
| ------------ | ------------------- |
| `username`   | WordPress username  |
| `email`      | User email address  |
| `password`   | User password       |
| `role`       | WordPress user role |
| `first_name` | User first name     |
| `last_name`  | User last name      |

> **Note:** Make sure your CSV headers match the fields supported by the plugin.

---

## 🚀 Installation

### Method 1 — WordPress Admin

1. Download or clone this repository.
2. Create a ZIP file of the plugin folder.
3. Log in to your WordPress dashboard.
4. Go to **Plugins → Add New Plugin**.
5. Click **Upload Plugin**.
6. Upload the plugin ZIP file.
7. Click **Install Now**.
8. Activate the plugin.

### Method 2 — Manual Installation

Copy the plugin folder into:

```text
/wp-content/plugins/
```

Then activate **Bulk User Importer** from:

```text
WordPress Dashboard → Plugins
```

---

## 🛠️ How to Use

1. Install and activate the plugin.
2. Open the **Bulk User Importer** section in your WordPress dashboard.
3. Prepare your CSV file.
4. Upload the CSV file.
5. Select the appropriate import options.
6. Start the import process.
7. Review the import results.

The plugin will create the WordPress user accounts based on the information provided in the CSV file.

---

## 🔒 Security

The plugin is designed for use by authorized WordPress administrators.

Recommended security practices:

* Only administrators should have access to user imports.
* Do not publicly share CSV files containing passwords.
* Use strong passwords for imported accounts.
* Delete uploaded CSV files after completing an import.
* Always back up your WordPress database before performing a bulk import.

---

## 💻 Requirements

* **WordPress:** 5.8+
* **PHP:** 7.4+
* **MySQL:** 5.7+ / MariaDB equivalent

> Requirements may vary depending on the version of the plugin.

---

## 📁 Project Structure

```text
bulk-user-importer-wordpress/
│
├── bulk-user-importer.php
├── includes/
├── admin/
├── assets/
├── readme.md
└── README.md
```

The exact structure may vary depending on the current version of the project.

---

## 🔧 Technologies

* PHP
* WordPress Plugin API
* WordPress Users API
* MySQL
* HTML
* CSS
* JavaScript
* CSV

---

## 🗺️ Roadmap

Planned improvements may include:

* [ ] Drag-and-drop CSV upload
* [ ] Import progress indicator
* [ ] Custom field mapping
* [ ] User meta import
* [ ] WooCommerce customer support
* [ ] Import logs
* [ ] Error report download
* [ ] Update existing users
* [ ] Custom role mapping
* [ ] Export users to CSV

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/new-feature
```

3. Make your changes.
4. Commit your changes.

```bash
git commit -m "Add new feature"
```

5. Push to your branch.

```bash
git push origin feature/new-feature
```

6. Open a Pull Request.

---

## 🐛 Bug Reports & Feature Requests

If you find a bug or have an idea for improving the plugin, please open an **Issue** in this repository.

When reporting a bug, include:

* WordPress version
* PHP version
* Plugin version
* CSV structure
* Error message
* Steps to reproduce the issue

---

## 📜 License

This project is licensed under the **GPL-2.0-or-later** license.

---

## 🔑 SEO Keywords

**WordPress Bulk User Importer, WordPress User Import Plugin, Bulk Import Users WordPress, Import WordPress Users from CSV, WordPress CSV User Importer, Bulk WordPress User Upload, WordPress User Management Plugin, CSV to WordPress Users, WordPress User Import Tool, Bulk Create WordPress Users**

---

## ⭐ Support

If this project helps you, consider giving the repository a ⭐ **Star** on GitHub.

**Built for WordPress administrators who need a simple way to manage users at scale.**
