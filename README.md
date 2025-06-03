# gam-user-reset
Automates Google Workspace account security actions using GAM — signs out user and forces password change.

# GAM Account Secure

A Python script to quickly secure Google Workspace accounts using [GAM](https://github.com/jay0lee/GAM).

---

## 🔧 Features
- ✅ Prompts for the compromised email address before executing
- ✅ Signs out a user from all active sessions
- ✅ Forces password reset on next login
- ✅ Uses GAM for direct admin control

Ideal for IT admins responding to:
- Suspicious activity
- Device theft
- Student misuse
- Fast access lockdowns

---

## 🚀 Usage

1. Make sure [GAM is installed and authorized](https://github.com/jay0lee/GAM/wiki)
2. Run the script in terminal:

```bash
python3 suspend_secure.py

