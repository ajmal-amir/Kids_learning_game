# 🌟 Learning Universe — Full Setup Guide

One file. Two worlds. Everything your daughter needs to start school confident.

---

## 🎮 What's Inside

### 🦉 Ollie's English World
| Game | Learns |
|---|---|
| ABC Land | All 26 letters + pictures + voice |
| Spell It! | Spell 3-letter words by tapping |
| Letter Hunt | Recognise letters by sight (10 rounds) |
| Word Match | Match pictures to words |

### 🤖 Zippy's Math World
| Game | Learns |
|---|---|
| Count It! | Count objects 1–9 |
| Add It Up! | Visual addition (1+1 to 5+5) |
| Shape Star | Name 8 shapes |
| Number Order | Tap 1→5 in sequence |

### 🔒 Parent Corner (PIN protected)
- ⏱ Live session timer visible at all times
- 📊 Today's stats: time, stars, letters learned, math games done
- ⚙️ Set child's name, parent email, SMS address, time limit, PIN
- 📧 One-tap email progress report
- 💬 One-tap SMS report (via email-to-text)
- 🔔 **Auto-report** sent when time limit is hit OR when she leaves the app

---

## 🚀 Deploy to GitHub Pages (5 minutes, free)

1. Go to [github.com](https://github.com) — sign up if needed
2. Click **+** → **New repository** → name it `learning-universe` → Public → **Create**
3. Click **Add file** → **Upload files** → drag in `index.html` → **Commit changes**
4. Go to **Settings** → **Pages** → Branch: **main** / root → **Save**
5. Live in ~2 min at: `https://YOUR-USERNAME.github.io/learning-universe/`

### 📱 Make it a Home Screen App (iPad/iPhone)
1. Open Safari → go to your link
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Name it "Learning Universe" → **Add**
5. Full-screen app on her home screen — no address bars! ✨

---

## 🔔 Parent Notification Setup

### Step 1 — Open Parent Corner
Tap the 🔒 button on the home screen. Default PIN is **1234**.

### Step 2 — Fill in Settings
- **Child's Name** — used in the report (e.g. "Aisha")
- **Parent Email** — receives the full progress report
- **Time Limit** — app will alert you and send a report when reached
- **Change PIN** — set your own 4-digit PIN

### Step 3 — SMS / Text Notifications (Email-to-Text)

Most US carriers let you receive emails as text messages for free.  
Enter your carrier's email-to-text address in the **SMS / Phone** field:

| Carrier | Format |
|---|---|
| AT&T | `10digitnumber@txt.att.net` |
| Verizon | `10digitnumber@vtext.com` |
| T-Mobile | `10digitnumber@tmomail.net` |
| Sprint | `10digitnumber@messaging.sprintpcs.com` |
| US Cellular | `10digitnumber@email.uscc.net` |
| Cricket | `10digitnumber@mms.cricketwireless.net` |

**Example:** If your AT&T number is (704) 555-1234, enter: `7045551234@txt.att.net`

### How Notifications Work

| Event | What happens |
|---|---|
| Time limit reached | Alert appears on screen + auto report sent |
| App minimized / closed | Auto report sent in background |
| Tap 📧 Email Report | Opens email app pre-filled with full progress |
| Tap 💬 SMS Report | Sends short summary to your phone |

**Note:** The auto-report uses your device's default email app (mailto:), which requires the email app to be configured on the device running the game.

---

## 📊 Progress Report Contents

Each report includes:
- Date and total learning time today
- ⭐ Stars earned (session + total)
- 📖 Letters learned (count + which ones: A, B, C…)
- 🔢 Math games completed

---

## 🛠️ Customise It

All content is in the single `index.html` file.

**Add new words to Spell It!** — find `SPELL_WORDS`:
```js
{w:'RAT', e:'🐀', h:'A tiny little rat!'},
```

**Change time limit default** — find `<option value="20">` and change `selected` attribute.

**Change default PIN** — find `pin:'1234'` in the settings object and change it.

---

Made with ❤️ for every child about to begin their adventure.
