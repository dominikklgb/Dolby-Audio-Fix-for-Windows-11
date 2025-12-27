# Bug Report or Question Template

> 📝 **Before posting:** Check the [FAQ](./FAQ.md) and [Troubleshooting](./GUIDE.md#-troubleshooting) sections—your answer might already be there!

---

## 🐛 Issue Type
- [ ] **Bug Report** - Something doesn't work as described in the guide
- [ ] **Question** - Need help or clarification
- [ ] **Feature Request** - Suggest a new section/improvement
- [ ] **Other** - (describe below)

---

## ❌ The Problem

**What went wrong?** (Be specific)

```
Example: "Following Phase 2.1, Dolby Access crashes immediately when I try to select 'Theatre' mode"
```

---

## 🖥️ System Information

**Required to help you:**

- **Windows Build:** (Find in Settings → System → About → Windows specifications)
  ```
  Example: Windows 11 Build 26100
  ```

- **Audio Device:** (Settings → System → Sound → Advanced → See all)
  ```
  Example: Realtek(R) Audio / NVIDIA High Definition Audio
  ```

- **Have you installed codec already?**
  - [ ] Yes
  - [ ] No
  - [ ] Not sure

---

## 📋 Steps Taken So Far

**What have you already tried?** (So we don't suggest it again)

- [ ] Followed Phase 1 (Codec Installation)
- [ ] Followed Phase 2 (Dolby Configuration)
- [ ] Rebooted PC
- [ ] Cleared Netflix cache
- [ ] Checked Diagnostics section
- [ ] Reinstalled Dolby Access
- [ ] Updated audio drivers
- [ ] **Other:** (describe)

---

## 🔧 Diagnostic Information

**Run this to help diagnose:**

### Method 1: Codec Installation Check
```powershell
# Open PowerShell as Administrator and paste:
Get-WindowsOptionalFeature -Online | Where-Object {$_.FeatureName -match "Dolby"}
```

**Output (paste here):**
```
[PASTE OUTPUT HERE]
```

---

### Method 2: Audio Format Check
1. Settings → System → Sound → Volume mixer
2. Play Netflix Dolby content
3. What audio format shows? (PCM / AC-3 / Dolby Atmos / etc.)

**Format shown:** `[Type here]`

---

### Method 3: Dolby Access Version
1. Open Dolby Access
2. Look for Settings or About
3. What version number?

**Dolby Access Version:** `[Paste here]`

---

## 🎬 Expected vs Actual

**What should happen:**
```
[From the guide: describe expected behavior]
```

**What actually happens:**
```
[Describe the actual behavior]
```

---

## 📸 Screenshots (Optional but Helpful!)

If you can, attach:
- Error message you see (screenshot)
- Windows Sound settings panel (screenshot)
- Dolby Access settings (screenshot)

---

## 🔗 Additional Context

Anything else that might help?
- When did this start?
- Did it work before?
- Other apps with Dolby (gaming, etc.)?

---

## ✅ Checklist Before Posting

- [ ] I've read the [GUIDE.md](./GUIDE.md) completely
- [ ] I've checked the [FAQ.md](./FAQ.md)
- [ ] I've checked the [Troubleshooting section](./GUIDE.md#-troubleshooting)
- [ ] I've searched existing issues (no duplicate)
- [ ] I've provided system info (Windows build, audio device)
- [ ] I've included what I've already tried

---

## 📞 Response Time

Please be patient! We're volunteers. Expected response: 24-72 hours.

**In the meantime:**
- Check [Troubleshooting](./GUIDE.md#-troubleshooting) for similar issues
- Try the diagnostic commands above
- Search Google for your specific error message

---

## 🙏 Thank You!

Your issue helps us make this guide better for everyone. Merci! 🇫🇷
