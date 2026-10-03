<div align="center">
<img width="2560" height="1140" alt="20260928_202316 (1)" src="https://github.com/user-attachments/assets/5c49d83c-911e-4682-a1fc-ef6a3cff804b" />

# 🎤 SongHub Karaoke

**Free, offline karaoke player for your PC — MIDI, MP3, MP4, CDG and Chorus, all in one app.**

*Libre, offline na karaoke player para sa PC — MIDI, MP3, MP4, CDG at Chorus, nasa iisang app.*

![Status](https://img.shields.io/badge/status-beta%20stable-brightgreen)
![Price](https://img.shields.io/badge/price-FREE-blue)
![Mode](https://img.shields.io/badge/mode-offline-orange)
![Language](https://img.shields.io/badge/lang-English%20%7C%20Tagalog-yellow)

[English](#-english) • [Tagalog](#-tagalog)

</div>

---

# 🇬🇧 English

## 📖 What is SongHub?

SongHub is a **free karaoke application for PC** that works completely **offline**. No activation, no subscription, no internet needed. You bring your own legally obtained karaoke files, point SongHub to your folders, and it builds a searchable song list with song numbers, just like a real karaoke machine.

It is made for families, singers, and karaoke fans who want a simple, good-looking karaoke setup at home.

> 💬 Official page: <https://www.facebook.com/songhubpc>

## ⚙️ Requirements
- Recommended Windows 10, Windows 11 64 bit Operating System, supports also Windows 8.1 (need some requirements)
- 2GB of RAM
- On-board Graphics or GPU

## ✨ Features

### 🎶 Supported song formats
| Format | Description |
|---|---|
| **MIDI** (`.mid`) | Classic karaoke with synchronized, highlighted lyrics |
| **MP3** (`.mp3`) | Audio karaoke tracks |
| **MP4** (`.mp4`) | Karaoke music videos |
| **CDG** (`.mp3` + `.cdg`) | Western-style CD+Graphics karaoke |
| **Chorus** (`.mid` + `.cho`) | MIDI with a chorus / multiplex vocal track (`.cho` is an MP3 file) |

### 🖥️ On-screen experience
- 2-line and **4-line lyric display** with per-word highlighting
- Song title / singer intro screen and **"Next Song"** information
- **Reservation queue** (just like a karaoke machine), including priority "first reserve"
- Background videos (**BGV**) behind your lyrics
- **Score system** with several animated styles (Default, New, Lotto, Mega) and customizable colors and backgrounds
- Fullscreen mode

### 🎛️ Controls while singing
- **Key** up / down (transpose) and **Tempo** up / down
- **Melody** on / off (guide vocal)
- **Chorus / MPX** toggle for songs with a chorus track
- Pause, stop, next song

### 🔍 Finding songs
- Search by **song number**, **title**, or **artist**
- Filter by language/country
- Duplicate song filter (optional)

### 📱 SmartLink (remote)
- Control SongHub from other devices on your network
- **Improved broadcasting system** and a display of how many devices are connected

### 🌐 Languages
- **English** and **Tagalog** interface

---

## 🚀 Getting Started

1. Download SongHub from the [official page](https://www.facebook.com/songhubpc) or from this repository's **Releases**.
2. Run the app.
3. Add your song folders (see below).
4. Press **F1** and start singing!

### ⌨️ Handy keyboard shortcuts

| Key | Action |
|---|---|
| `F1` | Open song search / song menu |
| `F9` | Open **Settings** |
| `F11` | Toggle fullscreen |
| `F3` | Toggle Chorus / MPX |
| `F5` | (In search) Change language/country filter |
| `F6` | (In search) Switch Title ↔ Artist search |
| `F7` | (In search) Switch number ↔ letter input |
| `F8` | (In search) Play the selected song |
| `F12` | Song list (after adding a database, as per changelog) |

---

## 📂 How to add songs

SongHub uses a **User Library Content Database**. Follow these steps:

1. Press **Settings (F9)**.
2. Under **"User Library Content Database"**, click **New Database**.
3. Type a file name and click **Save**.
4. Click **Add Folders** and select the folders that contain your songs.
5. In the **Folder options** dialog that appears:
   - Choose the **Language encoding** (useful if one folder has songs in different languages).
   - Set the **Starting Number** (see below).
6. *(Optional)* Tick **Enable duplicate song filter**.
7. Click **Scan User Contents**, then press **OK** to apply the changes.
8. Check your list by pressing **F1** and **F12**.

> 🔄 Added new files to a folder later? Just click **Scan User Contents** again and they will be added to the list.

### 🗂️ File naming guide

Your files should be named in one of these formats:

```text
00123 - Title - Singer.mid
00456 - Title - Singer.mp3
00789 - Title - Singer.mp4
12345 - Title - Singer.cdg      ← CDG song (needs matching .mp3)
12345 - Title - Singer.mp3      ← CDG song audio
67890 - Title - Singer.cho      ← Chorus song (MP3 chorus track)
67890 - Title - Singer.mid      ← Chorus song (MIDI)
Title - Singer.mid              ← no number (auto-assigned)
filename.mid                    ← any name (auto-assigned)
```

> For **CDG** and **Chorus** songs, both files must share the **same number** (e.g. `12345`).

### 🔢 Starting Number explained

| You enter | Result |
|---|---|
| *(nothing)* | Uses the **original number** from the file name |
| `0` | Numbers songs **sequentially** (1, 2, 3, …) |
| e.g. `100000` | Numbers start from there: `100001`, `100002`, `100043`, … |

---

## 🎨 Customization

Open **Settings (F9)** to personalize SongHub:

- **Fonts and colors** of lyrics, titles and "Next Song" information
- **Lyric layout:** 2-line or 4-line display
- **Score style** and its colors/background (Default, New, Lotto, Mega)
- **Background videos (BGV)** and per-song music videos
- **Interface language** (English / Tagalog)
- **Backup and restore** your settings
- **Changelogs** and **About SongHub** are also available in Settings

---

## 🆕 What's new in 1.14

- Improved **SmartLink** broadcasting system
- New **User Library Content Database** system (the old IDX Songpack system was removed due to policy and abuse concerns)
- Added **CDG** support (MP3 + CDG)
- Added **Chorus** support (MIDI + `.cho`)
- SmartLink shows the **number of connected devices**
- Improved Settings, fixed *Restore Config*, and better overall performance

See [`Changelogs.md`](Changelogs.md) for the full history.

---

## ⚠️ Important Notice

- SongHub is **100% FREE**: no payment, no activation, no subscription. It is **not for sale**, and selling it is against the law.
- SongHub does **not** provide song files. Use only files you **legally own**, for **personal use**. **Do not share or distribute** them, to avoid copyright issues.
- Buy content from producers and programmers, or download from their official websites. Avoid unauthorized sources.
- SongHub is **not allowed for commercial / business use**.

## ❤️ Support the project

SongHub is free and always will be. If you want to support our work, you can donate. Message us on our official page: <https://www.facebook.com/songhubpc>

## 👥 Credits

SongHub is made by **JPEE SEPEDA (this GitHub owner/page)**, **NOTZKIE KETCHUM**, and **XEAN CONCEPCION**

---

# 🇵🇭 Tagalog

## 📖 Ano ang SongHub?

Ang SongHub ay isang **libreng karaoke application para sa PC** na gumagana nang **offline**. Walang activation, walang subscription, at hindi kailangan ng internet. Ilagay lang ang sarili mong karaoke files, i-point ang SongHub sa iyong mga folder, at gagawa ito ng listahan ng kanta na may song number, parang totoong karaoke machine.

Para ito sa pamilya, mga mahilig kumanta, at karaoke fans na gusto ng simple at magandang karaoke sa bahay.

> 💬 Opisyal na page: <https://www.facebook.com/songhubpc>

## ⚙️ Requirements
- Recommended Windows 10, Windows 11 64 bit Operating System, supports also Windows 8.1 (need some requirements)
- 2GB of RAM
- On-board Graphics or GPU
  
## ✨ Mga Features

### 🎶 Mga sinusuportahang format
| Format | Paliwanag |
|---|---|
| **MIDI** (`.mid`) | Klasikong karaoke na may naka-sync at naka-highlight na lyrics |
| **MP3** (`.mp3`) | Karaoke audio tracks |
| **MP4** (`.mp4`) | Karaoke music videos |
| **CDG** (`.mp3` + `.cdg`) | Western-style na CD+Graphics karaoke |
| **Chorus** (`.mid` + `.cho`) | MIDI na may chorus / multiplex vocal (ang `.cho` ay isang MP3 file) |

### 🖥️ Sa screen
- **2-line** at **4-line** na lyrics, may highlight kada salita
- Intro screen ng title at singer, at impormasyon ng **"Next Song"**
- **Reservation queue** (tulad ng karaoke machine), pati **"first reserve"** para unahin ang isang kanta
- **Background videos (BGV)** sa likod ng lyrics
- **Score system** na may iba't ibang animated styles (Default, New, Lotto, Mega), at pwedeng palitan ang kulay at background
- Fullscreen mode

### 🎛️ Controls habang kumakanta
- **Key** pataas / pababa at **Tempo** pataas / pababa
- **Melody** on / off (guide vocal)
- **Chorus / MPX** toggle para sa mga kantang may chorus
- Pause, stop, next

### 🔍 Paghahanap ng kanta
- Maghanap gamit ang **song number**, **title**, o **artist**
- I-filter ayon sa language/bansa
- Duplicate song filter (optional)

### 📱 SmartLink (remote)
- Makokontrol ang SongHub gamit ang ibang device sa inyong network
- **Pinahusay na broadcasting system** at makikita kung ilang device ang konektado

### 🌐 Wika
- Interface sa **English** at **Tagalog**

---

## 🚀 Paano Magsimula

1. I-download ang SongHub sa [opisyal na page](https://www.facebook.com/songhubpc) o sa **Releases** ng repository na ito.
2. Buksan ang app.
3. Mag-add ng song folders (tingnan sa ibaba).
4. Pindutin ang **F1** at kumanta na!

### ⌨️ Mga madaling shortcut

| Key | Gamit |
|---|---|
| `F1` | Buksan ang song search / song menu |
| `F9` | Buksan ang **Settings** |
| `F11` | Fullscreen |
| `F3` | Chorus / MPX on-off |
| `F5` | (Sa search) Palitan ang language/country filter |
| `F6` | (Sa search) Title ↔ Artist |
| `F7` | (Sa search) Number ↔ letters |
| `F8` | (Sa search) I-play ang napiling kanta |
| `F12` | Song list (pagkatapos mag-add ng database) |

---

## 📂 Paano mag-add ng kanta?

Gumagamit ang SongHub ng **User Library Content Database**. Sundin ang mga hakbang:

1. Pindutin ang **Settings (F9)**.
2. Sa **"User Library Content Database"**, i-click ang **New Database**.
3. Ilagay ang File name at i-click ang **Save**.
4. I-click ang **Add Folders** at piliin ang mga folder na may laman na kanta.
5. Sa lalabas na **Folder options** dialog:
   - Piliin ang **Language encoding** (kung may kanta kayong international sa iisang folder).
   - Ilagay ang **Starting Number** (tingnan sa ibaba).
6. *(Optional)* I-click ang **Enable duplicate song filter**.
7. I-click ang **Scan User Contents**, tapos **OK** para ma-apply.
8. Tingnan ang song list sa pagpindot ng **F1** at **F12**.

> 🔄 May dinagdag kang file sa folder? I-click lang ulit ang **Scan User Contents** para maidagdag ito sa listahan.

### 🗂️ Tamang pangalan ng files

Dapat ganito ang itsura ng mga files:

```text
00123 - Title - Singer.mid
00456 - Title - Singer.mp3
00789 - Title - Singer.mp4
12345 - Title - Singer.cdg      ← CDG song (kailangan ng katapat na .mp3)
12345 - Title - Singer.mp3      ← audio ng CDG song
67890 - Title - Singer.cho      ← Chorus song (MP3 chorus track)
67890 - Title - Singer.mid      ← Chorus song (MIDI)
Title - Singer.mid              ← walang number (automatic ang number)
filename.mid                    ← kahit anong pangalan (automatic ang number)
```

> Para sa **CDG** at **Chorus**, dapat **pareho ang number** ng dalawang file (hal. `12345`).

### 🔢 Ano ang Starting Number?

| Ilalagay mo | Resulta |
|---|---|
| *(wala)* | Gagamitin ang **orihinal na number** sa pangalan ng file |
| `0` | **Sunod-sunod** ang bilang (1, 2, 3, …) |
| hal. `100000` | Magsisimula doon: `100001`, `100002`, `100043`, … |

---

## 🎨 Customization

Buksan ang **Settings (F9)** para i-personalize ang SongHub:

- **Font at kulay** ng lyrics, title, at "Next Song" info
- **Lyrics layout:** 2-line o 4-line
- **Score style** at kulay/background nito (Default, New, Lotto, Mega)
- **Background videos (BGV)** at music videos kada kanta
- **Wika ng interface** (English / Tagalog)
- **Backup at restore** ng configuration
- Nasa Settings din ang **Changelogs** at **About SongHub**

---

## 🆕 Ano ang bago sa 1.14

- Pinahusay na **SmartLink** broadcasting system
- Bagong **User Library Content Database** system (inalis na ang IDX Songpack system dahil sa policies at abuso sa pamamahagi ng personal/customized na songfiles)
- Dagdag na suporta sa **CDG** (MP3 + CDG)
- Dagdag na suporta sa **Chorus** (MIDI + `.cho`)
- Makikita na ng SmartLink ang **bilang ng konektadong device**
- Mas magandang Settings, naayos ang *Restore Config*, at mas mabilis na performance

Tingnan ang [`Changelogs.md`](Changelogs.md) para sa buong kasaysayan.

---

## ⚠️ Paalala

- Ang SongHub ay **LIBRE**: walang bayad, walang activation, walang subscription. **Hindi ito ibinebenta** at labag sa batas ang pagbebenta nito.
- **Hindi** kami nagbibigay ng song files para sa ligtas at masayang paggamit ng app. Gamitin lang ang files na **legal mong pag-aari**, para sa **personal na gamit**. **Huwag ipamahagi** sa iba para maiwasan ang Copyright issues.
- Bumili ng contents mula sa Producers at Programmers, o mag-download sa kanilang opisyal na website. Iwasan ang files mula sa unauthorized sources.
- **Hindi pinahihintulutan** ang paggamit nito sa negosyo.

## ❤️ Suportahan kami

Ang SongHub ay libre at mananatiling libre. Kung nais mong suportahan ang aming trabaho, maaari kang magbigay ng donasyon. Mag-message sa aming official page: <https://www.facebook.com/songhubpc>

## 👥 Credits

Gawa nina **JPEE SEPEDA (ang GitHub owner/page)**, **NOTZKIE KETCHUM**, at si **XEAN CONCEPCION**

---

<div align="center">

🎤 *Happy singing! / Masayang pagkanta!* 🎶

</div>
