<div align="center">
  <img src="https://github.com/user-attachments/assets/661221d5-4bae-4776-9fbf-97e28b57207f" width="256" alt="شعار DotsOS">
  <br/>
  <h1 align="center">DotsOS</h1>
  <p align="center">بيئة متكاملة مبنية على نظام Arch توفر سهولة التثبيت وتخصيصاً واسع النطاق.</p>
    </a>
  </p>
</div>
<br />

https://github.com/user-attachments/assets/ac27173d-74d9-4579-9fe6-887f501ab265

> **تجربة متكاملة، أنيقة، وسهلة الاستخدام مبنية على نظام Arch Linux.**

نظام **DotsOS** هو بيئة متكاملة بالكامل مبنية على **Arch Linux**، مصممة لتكون جاهزة للاستخدام فور تثبيتها دون أي عناء. يوفر النظام واجهات مستقرة ومظهراً لا يقتصر على الجمال فحسب، بل يتميز بالموثوقية العالية وسهولة الاستخدام، وذلك بفضل تركيزنا الكبير على التحسينات وتعديلات النظام.

## ✨ الميزات الرئيسية

*   **مبني على Arch Linux:** استمتع بأحدث الحزم ونموذج الإصدار المستمر (Rolling release) إلى جانب القوة المطلقة في التخصيص.
*   **مدير النوافذ Hyprland Wayland:** تجربة Wayland حديثة وسلسة للغاية، تتميز بحركات (Animations) رائعة وأداء لا مثيل له.
*   **Caelestia:** يدمج ملفات [caelestia-dots](https://github.com/caelestia-dots) الأنيقة لتقديم واجهة مستخدم جذابة بصرياً، متماسكة، وحديثة.
*   **Caelestia SDDM:** انطباع أول ساحر في كل مرة تقوم فيها بتشغيل جهازك، بفضل سمة [caelestia-sddm](https://github.com/ItsABigIgloo/caelestia-sddm) الجميلة.
*   **سهل الاستخدام:** ودّع الساعات الطويلة من الإعداد! النظام مُعد مسبقاً ليناسب كلاً من المبتدئين والمستخدمين المحترفين على حد سواء.
*   **تجربة محسّنة ومستقرة:** قمنا بتنفيذ **العديد من التعديلات والإصلاحات** للمشاكل الشائعة في بيئات Hyprland، مما يضمن سير عمل مستقر وموثوق وخالٍ من الانهيارات المفاجئة.

## 📸 لقطات الشاشة

| محمل الإقلاع (Limine) | شاشة تسجيل الدخول (SDDM) | شاشة القفل |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/8f121115-23b0-4f32-b199-2c4661419f3c" width="400" alt="Limine Screen"> | <img src="https://github.com/user-attachments/assets/3a21a2d3-542a-42fe-b69c-40978eadd42b" width="400" alt="SDDM Screen"> | <img src="https://github.com/user-attachments/assets/21f984bc-2a4b-41f8-90d8-512a326a0b57" width="400" alt="Lock Screen"> |

| سطح المكتب (Hyprland) | اللوحات (Panels) | الإشعارات |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/22924c33-8105-480a-b16d-12e76c19021f" width="400" alt="Desktop"> | <img src="https://github.com/user-attachments/assets/35648809-2bb7-42c5-bdeb-80d10fc66b93" width="400" alt="Caelestia Shell"> | <img src="https://github.com/user-attachments/assets/3170f3cc-7795-4ad8-8718-21b7c5af404a" width="400" alt="Notifications"> |

## 🚀 التثبيت

**قريباً**

## ⚙️ الإعدادات (Configuration)

يتبع هذا التكوين بنية تركيبية (Modular) للحفاظ على تنظيم الإعدادات وسهولة صيانتها. وفيما يلي تفصيل لملفات التكوين:

**Hyprland (Caelestia Dots)**
*   **المتغيرات (Variables)** `~/.config/hypr/variables.conf` — يحدد الثوابت العامة للألوان، والأحجام، وتبديل السمات المستخدمة في جميع أنحاء الإعدادات.
*   **Hyprland الأساسي** `~/.config/hypr/hyprland.conf` — نقطة الدخول الرئيسية التي تستدعي جميع ملفات التكوين التركيبية الأخرى.
*   **الحركات (Animations)** `~/.config/hypr/hyprland/animations.conf` — منحنيات Bezier المخصصة وقواعد الحركة للنوافذ والطبقات ومساحات العمل.
*   **الزخرفة (Decoration)** `~/.config/hypr/hyprland/decoration.conf` — التصميم المرئي بما في ذلك تدوير الزوايا، وتأثيرات تمويه (Blur) الخلفية، وظلال النوافذ.
*   **بيئة النظام (Env)** `~/.config/hypr/hyprland/env.conf` — متغيرات البيئة لخلفيات أدوات التطوير (QT, GTK)، ومواصفات XDG، وسمات مؤشر الماوس.
*   **التنفيذ (Execs)** `~/.config/hypr/hyprland/execs.conf` — تطبيقات بدء التشغيل التلقائي، والخدمات الخلفية (Daemons)، وخدمات النظام التي تبدأ عند تسجيل الدخول.
*   **عام (General)** `~/.config/hypr/hyprland/general.conf` — إعدادات التخطيط الأساسية، والمسافات بين النوافذ، وأحجام الحدود، وألوان الحدود النشطة/غير النشطة.
*   **الإيماءات (Gestures)** `~/.config/hypr/hyprland/gestures.conf` — إعدادات التمرير بين مساحات العمل عبر لوحة اللمس (Touchpad) وإيماءات الأصابع المتعددة.
*   **المجموعات (Group)** `~/.config/hypr/hyprland/group.conf` — تكوين مجموعات النوافذ المبوبة (Tabbed)، بما في ذلك خطوط وألوان شريط المجموعة.
*   **الإدخال (Input)** `~/.config/hypr/hyprland/input.conf` — تخطيطات لوحة المفاتيح (الإنجليزية/العربية)، ومعدلات التكرار، وإعدادات حساسية لوحة اللمس/الماوس.
*   **الاختصارات (Keybinds)** `~/.config/hypr/hyprland/keybinds.conf` — قائمة شاملة باختصارات لوحة المفاتيح لتشغيل التطبيقات، وإدارة النوافذ، والتحكم في الوسائط.
*   **متفرقات (Misc)** `~/.config/hypr/hyprland/misc.conf` — إعدادات متنوعة لمعدل التحديث المتغير (VRR)، وإدارة الطاقة (DPMS)، وسلوك التركيز على النوافذ.
*   **القواعد (Rules)** `~/.config/hypr/hyprland/rules.conf` — قواعد محددة للتحكم في كيفية تصرف تطبيقات معينة (العائمة، الشفافية، التعيين لمساحة عمل محددة).
*   **التمرير (Scrolling)** `~/.config/hypr/hyprland/scrolling.conf` — تكوين التخطيطات القائمة على الأعمدة وسلوك تتبع التركيز.

**النظام (System)**
*   **محمل الإقلاع (Bootloader)** `/boot/limine/limine.conf`
*   **شاشة الإقلاع (Plymouth)** `/usr/share/plymouth/themes/DotsOS/DotsOS.script`

## 🙏 شكر وتقدير

لم يكن هذا المشروع ليرى النور لولا هذه المشاريع مفتوحة المصدر الرائعة. شكر خاص لـ:

*   **[Arch Linux](https://archlinux.org/)** - لنظام التشغيل الأساسي القوي والمتين.
*   **[caelestia-dots](https://github.com/caelestia-dots)** - لمكونات واجهة المستخدم الرائعة واستلهام ملفات التكوين (dotfiles) الأساسية.
*   **[caelestia-sddm](https://github.com/ItsABigIgloo/caelestia-sddm)** - لسمة مدير تسجيل الدخول الجميلة.
*   **[Quickshell](https://quickshell.org)** - الصدفة (Shell) الأساسية التي تشغل نظام التشغيل، والمعدلة بتكويناتنا الخاصة.

---
أصبح هذا المشروع ممكناً بفضل مساهمات:

* [Khalil_56](https://github.com/Khalilw5556)
* [Roitsc](https://github.com/Roitsc)

## 📜 الترخيص

هذا المشروع مرخص بموجب **[رخصة جنو العمومية الإصدار 3.0 (GPLv3)](https://github.com/DotsOS/.github/blob/main/LICENSE)**. 

لا تتردد في استخدامه، وتعديله، ومشاركته مع مجتمع لينكس! *ملاحظة: أي تعديلات أو أعمال مشتقة يتم توزيعها يجب أن تكون أيضاً مفتوحة المصدر ومرخصة بموجب ترخيص GPLv3.*
