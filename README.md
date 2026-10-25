<p align="center">
  <img src="icon.png" width="128" alt="Veyra Player icon">
</p>

<h1 align="center">Veyra Player</h1>

<p align="center">
  A Windows video and audio player that stays out of your way.<br>
  Hidden controls, episode folders, resume where you left off, themes, and in-app updates.
</p>

<p align="center">
  <a href="https://github.com/nova-faye/veyra-updates/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/nova-faye/veyra-updates?color=ad9d85&labelColor=1c1c24"></a>
  <a href="https://github.com/nova-faye/veyra-updates/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/nova-faye/veyra-updates/total?color=ad9d85&labelColor=1c1c24"></a>
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%2F11-ad9d85?labelColor=1c1c24">
</p>

<p align="center">
  <b>English</b> · <a href="#العربية">العربية</a>
</p>

---

## Download

**[Download the latest version](https://github.com/nova-faye/veyra-updates/releases/latest)**, then run `Veyra-Player-Setup-x.x.x.exe`.

- Windows 10 or 11, 64-bit
- Website: https://nova-faye.github.io/veyra-updates/

> Windows may show a SmartScreen warning because the installer isn't code-signed yet. Click **More info**, then **Run anyway**.

## Features

### A clean viewing experience
- **Hidden interface.** The controls and the mouse cursor stay hidden, even when you move the mouse. Press `Space` to show or hide them.
- **Clean screenshots.** Press `S` to save the current frame to your desktop as a PNG at the video's original resolution, with no interface in it.
- **Keyboard first.** Every action has a shortcut, and clicking the video plays or pauses it. Double-click for fullscreen.
- **Full playback controls.** Seek bar, volume and mute, speed from 0.5x to 2x, previous and next, and fullscreen.
- **Skip the intro.** One key jumps past the opening. Set the length (5 to 600 seconds) once in Settings.
- **Autoplay the next episode.** On by default, and you can turn it off in Settings.
- **Subtitles.** Put an `.srt` or `.vtt` file with the same name next to the video and it loads automatically.
- **Audio files too.** Plays MP3, M4A, FLAC, WAV, OGG, Opus and AAC. Audio shows a music screen with the track name, and appears as "Track 3/12" in your history.

### Your library
- **Folders become seasons.** Pick a folder, or drag it onto the window, and every video or audio file inside appears as an episode, sorted properly (episode 2 before episode 10), subfolders included.
- **Episode list.** Press `L` to see all episodes in the folder, with the current one highlighted. Click any to jump to it.
- **Resume where you left off.** The app remembers your position in every episode and marks the ones you finished with a check.
- **Watch history.** Every show or folder you opened, with episode number, progress and last-watched time. Remove single items or clear everything.
- **Open with.** The installer adds Veyra Player to "Open with" for video and audio files. Open any episode and the whole folder is loaded, starting from that file. Opening another file reuses the same window.
- **Default player.** A button in Settings jumps straight to the Windows page where you can make Veyra Player your default.

### The home screen
- **Pick up where you left off.** Shows the last thing you watched with a thumbnail of the **exact frame you stopped at**, how far you got, and a button to resume (or to start the next episode if you finished).
- **Rows that follow your language.** Recent episodes, episodes you haven't watched yet, and other shows you watched appear as horizontal rows: left to right in English, right to left in Arabic. Scroll with the arrows.
- **Thumbnails.** The episode you stopped at shows the frame you stopped at. Finished or unwatched episodes show a random frame. They are cached on your computer and load only as they scroll into view, so big folders open fast.
- **Always-reachable buttons.** A top bar keeps Choose folder, Choose files, Feedback and Settings in reach, however many videos you have.

### Make it yours
- **9 themes:** Veyra (default), Dark, Light, Dracula, Nord, Solarized Dark, Solarized Light, Gruvbox and Catppuccin, with a color preview for each. The video area always stays black.
- **English and Arabic.** Switch the whole interface, including right-to-left layout, from Settings.
- **Organized Settings.** Appearance, Playback, Shortcuts, Feedback, and Updates & about.

### Updates and feedback
- **In-app updates.** Open Settings, click **Check for updates**, then **Update now**. The app downloads the update, installs it and restarts. It also checks quietly at startup (you can turn that off), and shows a banner on the home screen when a new version is ready.
- **What's new.** After each update, a window shows what changed, once. The full changelog is always available in Settings.
- **Feedback.** Report a bug, share an idea or send a comment from Settings. It opens a pre-filled GitHub issue that you can review before sending. Optional diagnostic info (app version, Windows version, language and theme) comes with a preview of exactly what is included. You can also just copy the text.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `Space` | Show or hide the interface |
| `K` or click | Play / pause |
| `I` | Skip the intro |
| `N` / `P` | Next / previous episode |
| `L` | Episode list |
| `H` | Watch history |
| `B` | Back to the home screen |
| `,` | Settings |
| `←` `→` | Seek 5 seconds |
| `↑` `↓` | Volume |
| `M` | Mute |
| `[` `]` | Playback speed |
| `F` or double-click | Fullscreen |
| `S` | Save a screenshot to the desktop |
| `O` | Open a folder |

## Supported formats

Veyra Player is built on the Chromium engine, so it plays what Chromium plays.

- **Video:** MP4, WebM, MKV, MOV, M4V, AVI, TS, WMV, FLV and OGV, as long as the codecs are supported (H.264, VP9, AAC, Opus and MP3 are the most common).
- **Audio:** MP3, M4A, FLAC, WAV, OGG, Opus and AAC.

A few things are not supported:

- Some audio formats such as AC3 and DTS
- HEVC (H.265) on computers without hardware support for it
- WMA audio
- Subtitles embedded inside MKV files, and `.ass` subtitles. Use external `.srt` or `.vtt` files instead
- Cover art inside audio files

If a file can't be played, the app tells you and you can jump to the next one.

## Privacy

Everything stays on your computer: history, playback positions, thumbnails and settings. The only network request the app makes is the update check to GitHub. Feedback only opens your browser, and nothing is sent until you press Submit on GitHub.

## Feedback

Use **Settings, then Feedback** inside the app, or open an issue in this repository.

---

<div dir="rtl">

<a name="العربية"></a>

## العربية

# Veyra Player

مشغل فيديو وصوت لويندوز ما يقف في طريقك. واجهة مخفية، مجلدات حلقات، استكمال من وين وقفت، ثيمات، وتحديث من داخل البرنامج.

## التحميل

**[حمّل آخر نسخة](https://github.com/nova-faye/veyra-updates/releases/latest)** وشغّل الملف `Veyra-Player-Setup-x.x.x.exe`.

- ويندوز 10 أو 11، 64 بت
- الموقع: https://nova-faye.github.io/veyra-updates/

> ممكن يطلع تحذير SmartScreen من ويندوز لأن المثبّت غير موقّع رقمياً بعد. اضغط **More info** ثم **Run anyway**.

## المميزات

### تجربة مشاهدة نظيفة
- **واجهة مخفية.** الأزرار ومؤشر الماوس يبقون مخفيين حتى لو حركت الماوس. اضغط `مسافة` تظهرهم وتخفيهم.
- **لقطات نظيفة.** اضغط `S` تنحفظ اللقطة على سطح المكتب بصيغة PNG بدقة الفيديو الأصلية، بدون أي واجهة فيها.
- **الكيبورد أولاً.** كل وظيفة لها اختصار، وكليك على الفيديو يشغّل ويوقف، ودبل كليك لملء الشاشة.
- **تحكم كامل بالتشغيل.** شريط التقدم، والصوت والكتم، والسرعة من 0.5x إلى 2x، والسابق والتالي، وملء الشاشة.
- **تخطي الانترو.** زر واحد يقفز فوق المقدمة، وتحدد المدة (من 5 إلى 600 ثانية) مرة وحدة في الإعدادات.
- **تشغيل الحلقة التالية تلقائياً.** مفعّل افتراضياً، وتقدر توقفه من الإعدادات.
- **الترجمة.** حط ملف `.srt` أو `.vtt` بنفس اسم الفيديو جنبه وتنحمل تلقائياً.
- **الملفات الصوتية كمان.** يشغّل MP3 وM4A وFLAC وWAV وOGG وOpus وAAC. الصوت يعرض شاشة موسيقى فيها اسم المقطع، ويظهر في السجل بشكل "المقطع 3/12".

### مكتبتك
- **المجلدات تصير مواسم.** اختر مجلد، أو اسحبه على النافذة، وكل فيديو أو ملف صوتي فيه يطلع كحلقة مرتبة بالطريقة الصحيحة (حلقة 2 قبل حلقة 10)، مع المجلدات الفرعية.
- **قائمة الحلقات.** اضغط `L` تشوف كل حلقات المجلد والحلقة الحالية مميزة، وكليك على أي وحدة ينقلك لها.
- **كمّل من وين وقفت.** البرنامج يتذكر مكانك في كل حلقة ويحط علامة ✓ على اللي خلصتها.
- **سجل المشاهدة.** كل مسلسل أو مجلد فتحته مع رقم الحلقة وتقدمك ووقت آخر مشاهدة. تقدر تحذف عنصر أو تمسح الكل.
- **فتح باستخدام.** المثبّت يضيف Veyra Player لقائمة "فتح باستخدام" لملفات الفيديو والصوت. افتح أي حلقة ويتحمل المجلد كامل ويبدأ من الملف اللي فتحته. وفتح ملف ثاني يستخدم نفس النافذة.
- **المشغل الافتراضي.** زر في الإعدادات ينقلك مباشرة لصفحة ويندوز اللي تخلي منها Veyra Player المشغل الافتراضي.

### الصفحة الرئيسية
- **كمّل من وين وقفت.** تعرض آخر شي شغلته مع صورة **اللقطة اللي وقفت عندها بالضبط**، وكم وصلت، وزر للاستكمال (أو لبدء الحلقة التالية لو خلصتها).
- **صفوف تمشي مع لغتك.** آخر الحلقات، والحلقات اللي ما تابعتها، وأشياء ثانية شاهدتها، كلها في صفوف أفقية: من اليسار لليمين بالإنجليزي، ومن اليمين لليسار بالعربي. وتتحرك فيها بالأسهم.
- **الصور المصغرة.** الحلقة اللي وقفت عندها تعرض اللقطة اللي وقفت عندها. والحلقات اللي خلصتها أو ما شغلتها تعرض لقطة عشوائية. تنحفظ على جهازك وتتحمل لما تظهر على الشاشة بس، فالمجلدات الكبيرة تفتح بسرعة.
- **أزرار دايماً قريبة.** شريط علوي ثابت فيه اختيار مجلد، واختيار ملفات، والملاحظات، والإعدادات، مهما كثرت الفيديوهات.

### خلّه على ذوقك
- **9 ثيمات:** Veyra (الأساسي) وDark وLight وDracula وNord وSolarized Dark وSolarized Light وGruvbox وCatppuccin، مع معاينة ألوان لكل ثيم. وخلفية الفيديو تبقى سوداء دايماً.
- **عربي وإنجليزي.** غيّر لغة الواجهة كاملة، مع اتجاه الكتابة من اليمين لليسار، من الإعدادات.
- **إعدادات مرتبة.** المظهر، والتشغيل، والاختصارات، والملاحظات، والتحديث وعن البرنامج.

### التحديث والملاحظات
- **تحديث من داخل البرنامج.** افتح الإعدادات، اضغط **تحقق من التحديثات** ثم **حدّث الآن**. البرنامج ينزّل التحديث ويثبّته ويعيد التشغيل. وهو يتحقق بهدوء كل ما تشغله (وتقدر توقف هذا)، ويطلع شريط في الصفحة الرئيسية لو فيه نسخة جديدة.
- **وش الجديد.** بعد كل تحديث تطلع نافذة تعرض التغييرات مرة وحدة. وسجل التغييرات الكامل متوفر دايماً في الإعدادات.
- **الملاحظات.** بلّغ عن مشكلة أو شارك فكرة أو أرسل تعليق من الإعدادات. يفتح لك Issue جاهز على GitHub تراجعه قبل ما ترسله. ومعلومات التشخيص الاختيارية (إصدار البرنامج وإصدار ويندوز واللغة والثيم) تجي مع معاينة لكل اللي بيتم إرساله. وتقدر تنسخ النص بس.

## الاختصارات

| الزر | الوظيفة |
|---|---|
| `مسافة` | إظهار أو إخفاء الواجهة |
| `K` أو كليك | تشغيل / إيقاف |
| `I` | تخطي الانترو |
| `N` / `P` | الحلقة التالية / السابقة |
| `L` | قائمة الحلقات |
| `H` | سجل المشاهدة |
| `B` | الرجوع للصفحة الرئيسية |
| `,` | الإعدادات |
| `←` `→` | تقديم وترجيع 5 ثواني |
| `↑` `↓` | الصوت |
| `M` | كتم |
| `[` `]` | سرعة التشغيل |
| `F` أو دبل كليك | ملء الشاشة |
| `S` | حفظ لقطة على سطح المكتب |
| `O` | فتح مجلد |

## الصيغ المدعومة

البرنامج مبني على محرك Chromium، فيشغّل اللي يشغله Chromium.

- **الفيديو:** MP4 وWebM وMKV وMOV وM4V وAVI وTS وWMV وFLV وOGV، بشرط إن الكودكات مدعومة (أشهرها H.264 وVP9 وAAC وOpus وMP3).
- **الصوت:** MP3 وM4A وFLAC وWAV وOGG وOpus وAAC.

وفيه أشياء غير مدعومة:

- بعض صيغ الصوت مثل AC3 وDTS
- HEVC (H.265) على الأجهزة اللي ما تدعمه بالعتاد
- صوت WMA
- الترجمة المدمجة داخل ملفات MKV وترجمة `.ass`. استخدم ملفات `.srt` أو `.vtt` خارجية بدلها
- صور الغلاف داخل الملفات الصوتية

لو ملف ما اشتغل، البرنامج ينبهك وتقدر تنتقل للي بعده.

## الخصوصية

كل شي يبقى على جهازك: السجل ومواضع الحلقات والصور المصغرة والإعدادات. الطلب الوحيد اللي يرسله البرنامج للإنترنت هو التحقق من التحديثات من GitHub. والملاحظات تفتح المتصفح بس، وما ينرسل شي لين تضغط Submit في GitHub.

## الملاحظات

استخدم **الإعدادات ثم الملاحظات** داخل البرنامج، أو افتح Issue في هذا الـ repository.

</div>
