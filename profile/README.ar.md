<div align="center">
  <img src="https://github.com/user-attachments/assets/661221d5-4bae-4776-9fbf-97e28b57207f" width="256" alt="DotsOS logo">
  <br/>
  <h1 align="center">DotsOS</h1>
  <p align="center">بيئة متكاملة مبنية على Arch توفر تثبيتاً سهلاً وتخصيصاً شاملاً.</p>
  
  <p align="center">
    For the English version:<br/>
    <a href="README.md">
      <!-- يمكنك استبدال الرابط أدناه بصورة لزر "Read in English" إن أردت -->
      <img src="https://img.shields.io/badge/Language-English-blue?style=for-the-badge" alt="Read in English">
    </a>
  </p>
</div>
<br />

https://github.com/user-attachments/assets/ac27173d-74d9-4579-9fe6-887f501ab265

> **تجربة متكاملة، أنيقة، وسهلة الاستخدام مبنية على Arch Linux.**

**DotsOS** هي بيئة متكاملة (Dotfiles) مبنية على **Arch Linux**، صُممت لتكون جاهزة للاستخدام مباشرة دون أي عناء. توفر النظام واجهات مستقرة وتجربة لا تقتصر على المظهر الجميل فحسب، بل تتميز بالموثوقية العالية وسهولة الاستخدام، وذلك بفضل تركيزنا الكبير على التحسينات وتعديلات النظام العميقة.

## ✨ الميزات الرئيسية

*   **مبنية على Arch Linux:** استمتع بأحدث الحزم ونظام التحديث المستمر (Rolling Release) مع قوة تخصيص مطلقة.
*   **مدير النوافذ Hyprland (Wayland):** تجربة Wayland حديثة وسلسة للغاية، تتميز بحركات (Animations) رائعة وأداء لا مثيل له.
*   **Caelestia:** دمج لتكوينات [caelestia-dots](https://github.com/caelestia-dots) الأنيقة لتقديم واجهة مستخدم مبهجة بصرياً، متناسقة وعصرية.
*   **Caelestia SDDM:** انطباع أول ساحر في كل مرة تقوم فيها بتشغيل جهازك، مع سمة [caelestia-sddm](https://github.com/ItsABigIgloo/caelestia-sddm) الجميلة.
*   **سهولة الاستخدام:** قل وداعاً لساعات من الإعداد والتكوين! النظام مُعد مسبقاً ليناسب كلاً من المبتدئين والمحترفين على حد سواء.
*   **تجربة مُحسنة ومستقرة:** قمنا بتنفيذ **العديد من التحسينات والإصلاحات** للمشكلات الشائعة في بيئات Hyprland، مما يضمن سير عمل مستقر، موثوق، وخالٍ من الانهيارات.

## 📸 لقطات الشاشة

| مدير الإقلاع (Limine) | شاشة تسجيل الدخول (SDDM) | شاشة القفل |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/8f121115-23b0-4f32-b199-2c4661419f3c" width="400" alt="Limine Screen"> | <img src="https://github.com/user-attachments/assets/3a21a2d3-542a-42fe-b69c-40978eadd42b" width="400" alt="SDDM Screen"> | <img src="https://github.com/user-attachments/assets/21f984bc-2a4b-41f8-90d8-512a326a0b57" width="400" alt="Lock Screen"> |

| سطح المكتب (Hyprland) | اللوحات (Panels) | الإشعارات |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/22924c33-8105-480a-b16d-12e76c19021f" width="400" alt="Desktop"> | <img src="https://github.com/user-attachments/assets/35648809-2bb7-42c5-bdeb-80d10fc66b93" width="400" alt="Caelestia Shell"> | <img src="https://github.com/user-attachments/assets/3170f3cc-7795-4ad8-8718-21b7c5af404a" width="400" alt="Notifications"> |

## 🚀 التثبيت

**قريباً**

## ⚙️ الإعدادات والتكوين

تتبع هذه الإعدادات هيكلية معيارية (Modular) للحفاظ على التنظيم وسهولة الصيانة. فيما يلي تفصيل لملفات التكوين:

**Hyprland (Caelestia Dots)**
*   **المتغيرات (Variables)** `~/.config/hypr/variables.conf` — يحدد الثوابت العامة للألوان، الأحجام، وتبديل السمات المستخدمة في جميع أنحاء النظام.
*   **Hyprland** `~/.config/hypr/hyprland.conf` — نقطة الإدخال الرئيسية التي تستدعي جميع ملفات التكوين المعيارية الأخرى.
*   **الحركات (Animations)** `~/.config/hypr/hyprland/animations.conf` — منحنيات (Bezier) مخصصة وقواعد حركية للنوافذ، الطبقات، ومساحات العمل.
*   **الزخرفة (Decoration)** `~/.config/hypr/hyprland/decoration.conf` — الأنماط المرئية بما في ذلك تدوير الزوايا، تأثيرات التمويه (Blur)، وظلال النوافذ.
*   **البيئة (Env)** `~/.config/hypr/hyprland/env.conf` — متغيرات البيئة للواجهات الخلفية (QT, GTK)، مواصفات XDG، وسمات المؤشر (Cursor).
*   **التنفيذ التلقائي (Execs)** `~/.config/hypr/hyprland/execs.conf` — التطبيقات التي تعمل تلقائياً، والخدمات التي تبدأ عند تسجيل الدخول.
*   **عام (General)** `~/.config/hypr/hyprland/general.conf` — إعدادات التخطيط الأساسية، الفراغات بين النوافذ، أحجام الحدود، وألوانها.
*   **الإيماءات (Gestures)** `~/.config/hypr/hyprland/gestures.conf` — إعدادات التمرير بين مساحات العمل عبر لوحة اللمس (Touchpad) ودعم الإيماءات متعددة الأصابع.
*   **المجموعات (Group)** `~/.config/hypr/hyprland/group.conf` — إعدادات مجموعات النوافذ المبوبة (Tabbed)، بما في ذلك خطوط وألوان الشريط.
*   **الإدخال (Input)** `~/.config/hypr/hyprland/input.conf` — تخطيطات لوحة المفاتيح (الإنجليزية/العربية)، معدلات التكرار، وحساسية الماوس/لوحة اللمس.
*   **الاختصارات (Keybinds)** `~/.config/hypr/hyprland/keybinds.conf` — قائمة شاملة باختصارات لوحة المفاتيح لتشغيل التطبيقات، إدارة النوافذ، والتحكم بالوسائط.
*   **متفرقات (Misc)** `~/.config/hypr/hyprland/misc.conf` — إعدادات متنوعة لمعدل التحديث المتغير (VRR)، إدارة الطاقة (DPMS)، وسلوك التركيز (Focus).
*   **القواعد (Rules)** `~/.config/hypr/hyprland/rules.conf` — قواعد محددة للتحكم في سلوك تطبيقات معينة (الطفو، الشفافية، التعيين لمساحة عمل معينة).
*   **التمرير (Scrolling)** `~/.config/hypr/hyprland/scrolling.conf` — إعدادات التخطيطات القائمة على الأعمدة وسلوك تتبع التركيز.

**النظام (System)**
*   **مدير الإقلاع** `/boot/limine/limine.conf`
*   **شاشة الإقلاع الرسومية (Plymouth)** `/usr/share/plymouth/themes/DotsOS/DotsOS.script`

## 🙏 شكر وتقدير

لم يكن هذا المشروع ممكناً لولا هذه المشاريع مفتوحة المصدر الرائعة. شكر خاص لـ:

*   **[Arch Linux](https://archlinux.org/)** - لتقديمهم نظام التشغيل الأساسي القوي والمتين.
*   **[caelestia-dots](https://github.com/caelestia-dots)** - لمكونات واجهة المستخدم الرائعة والإلهام الأساسي للمشروع.
*   **[caelestia-sddm](https://github.com/ItsABigIgloo/caelestia-sddm)** - لسمة مدير تسجيل الدخول الجميلة.
*   **[Quickshell](https://quickshell.org)** - الواجهة (Shell) الأساسية التي تشغل النظام، والمُعدلة بتكويناتنا الخاصة.

---
أصبح هذا المشروع ممكناً بفضل مساهمات كل من:

* [Khalil_56](https://github.com/Khalilw5556)
* [Roitsc](https://github.com/Roitsc)

## 📜 الترخيص

هذا المشروع مرخص بموجب **[رخصة جنو العمومية الإصدار 3 (GPLv3)](https://github.com/DotsOS/.github/blob/main/LICENSE)**. 

لا تتردد في استخدامه، تعديله، ومشاركته مع مجتمع لينكس! *ملاحظة: أي تعديلات أو أعمال مشتقة يتم توزيعها يجب أن تكون أيضاً مفتوحة المصدر ومرخصة بموجب نفس الرخصة (GPLv3).*
