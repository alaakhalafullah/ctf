# الخزنة المفقودة (Web CTF)

تحدّي ويب للمبتدئين من ملفين:

1. **اللي ما تشوفه العين**: الفلاج في تعليق HTML داخل `index.html` (View Source).
2. **ممنوع على الروبوتات**: `robots.txt` يكشف المسار السرّي `/hidden-vault-7k3q/` وفيه الفلاج.

## الحل (للمنظّم فقط)
1. `Ctrl+U` وابحث عن `FLAG`.
2. افتح `/robots.txt` ثم `/hidden-vault-7k3q/`.

## النشر على GitHub Pages
المستودع: `alaakhalafullah/ctf` ← الرابط: `https://alaakhalafullah.github.io/ctf/`

1. ارفع كل الملفات (بما فيها `.nojekyll`) لجذر المستودع.
2. Settings ← Pages ← Deploy from branch ← `main` / `(root)`.
3. اللاعب يدخل `https://alaakhalafullah.github.io/ctf/robots.txt` ويلقى المسار `/ctf/hidden-vault-7k3q/`.
