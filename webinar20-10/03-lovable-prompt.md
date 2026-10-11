# Lovable Prompt: Webinar Presentation

Copy everything inside the box below and paste it into Lovable as your first message.
After it builds, replace the [brackets] with your real content (or tell Lovable to do it).

---

```
Build a full-screen slide presentation web app for a live trading webinar.
It will be screen-shared on Zoom, so it must look great at 1920x1080 and be readable from a phone screen.

LANGUAGE & DIRECTION
- All slide text is in spoken Arabic. The whole app is RTL (dir="rtl").
- Use a strong Arabic font: "Cairo" or "Tajawal" from Google Fonts. Headlines bold and big (60–90px), body 32–40px.
- Very little text per slide. One idea per slide.

DESIGN
- Dark, premium trading look: near-black background (#0B0F14), white text, one accent color green (#22C55E) for wins/positive, red (#EF4444) only for "mistake"/"wrong" slides, and gold (#F5B800) for the offer and bonus.
- Subtle candlestick/chart pattern in the background at low opacity.
- Smooth fade/slide transitions between slides. Big numbers animate counting up when the slide appears.
- Small brand logo "90 Stox" in a corner of every slide.

CONTROLS
- Space, Enter, click, or the right-arrow key = next slide. Left-arrow key or Backspace = previous slide.
- "F" toggles fullscreen. "B" blacks out the screen.
- A presenter mode on a second tab (press "P") that shows the current slide, the next slide, speaker notes, and a running timer. Sync the two tabs (use BroadcastChannel).
- Progress bar at the bottom.
- Each slide has speaker notes (stored in a data file) shown only in presenter mode.

SLIDES (in order) — keep the Arabic exactly:

1. TITLE: "إستراتيجية وحدة. 7 سنين خبرة." / subtitle "ليش التريدينج أسهل بكتير مما بتفكر" / presenter name [اسمك] / date 20/10
2. "اكتبولي بالشات من وين انتو 👇" (big, centered, with a chat-bubble icon)
3. "مين فكّر إنه التريدينج مش إلو؟ اكتب 1 بالشات" (huge "1")
4. "الليلة رح تشوف 3 إشياء": three cards: (1) ليش التريدينج أسهل مما حكولك (2) الغلطة اللي 90% بيعملوها 🔒 (3) صفقتي من الأسبوع الماضي 🔒 — cards 2 and 3 show a lock icon (open loops)
5. "🎁 مفاجأة للي بضلّوا للآخر" (gift icon, gold, a little shimmer animation)
6. "قبل 7 سنين…" (story slide, dark, single line, cinematic)
7. "شارتي بالبداية" — image placeholder for a messy chart full of indicators
8. "…لحد ما لاحظت إشي واحد" (cliffhanger slide, mostly empty, "…" animates)
9. "أكبر كذبة بالتريدينج" (red accent)
10. SPLIT SCREEN: left "شارت المبتدئ" (image placeholder, messy) vs right "شارتي اليوم" (image placeholder, clean). Bottom: "شارتك بيشبه أي واحد؟ 👇"
11. "معظم المتداولين بيخسروا لأنهم بيعرفوا كتير، مش قليل" (big quote style)
12. "إستراتيجية وحدة. نفس الطريقة. كل مرة." (three lines appear one by one)
13. "ما عندي وقت…" (red, crossed out with an animated strike-through)
14. STUDENT DAY timeline: "[اسم الطالب] · [المهنة]" with 3 time blocks: "[وقت] · 20 دقيقة: بيدوّر على السيتاب", "إذا ما في سيتاب: بيسكّر", "[وقت] · 5 دقايق: بيشيك". Big result: "أقل من نص ساعة باليوم"
15. "قديش وقت عندك باليوم؟ اكتب بالشات 👇"
16. UNLOCK slide: lock opens with animation → "الغلطة اللي 90% بيعملوها"
17. "[الغلطة]" (red) + chart image placeholder
18. "مين عمل هالغلطة؟ اكتب 'أنا' 👇"
19. "اللي لاحظته:" → "[الفكرة الأساسية بجملة وحدة]" (green, closes the story)
20. "[اسم الإستراتيجية]" — title reveal, gold glow
21. THREE PARTS: three numbered cards appearing one by one: "1️⃣ [الجزء الأول]", "2️⃣ [الجزء الثاني]", "3️⃣ [الجزء الثالث]", each with a one-line description placeholder
22. Chart image placeholder with the 3 parts marked: "هيك بتبين عالشارت"
23. "بس فهمتوا الفكرة؟ اكتبوا 🔥"
24. Big split: "تعرف الإستراتيجية = 20%" vs "تطبّقها صح كل يوم = 80%" (animated bar showing 20/80)
25. "متل السواقة 🚗" — "ما حدا بيسوق لحاله بعد 10 دقايق شرح"
26. STUDENT RESULTS section title: "ما تصدقوني أنا. اسمعوا منهم."
27–29. One slide per student: name, photo placeholder, "قبل:" [...] → "بعد:" [...], big result number. Optional embedded video placeholder.
30. Small honest disclaimer slide: "نتايج حقيقية، بس مش ضمان. التريدينج فيه مخاطرة. أنا بضمنلك الطريقة والمرافقة. الالتزام عليك."
31. "مين جاهز يسمع عن البرنامج؟ اكتب 'جاهز' 👇"
32. OFFER TITLE: "90 Stox" huge, gold, subtitle "90 يوم · إستراتيجية وحدة · تتداول لحالك وبثقة" + "الفوج الجاي: [تاريخ البداية]"
33. WHAT YOU GET: checklist with green checks appearing one by one: [live sessions], [the full strategy step by step], [private community], [live trading with me], [extra]
34. VALUE: "قديش بيكلّفك تتعلّم لحالك؟" → "سنين + خسارات بالسوق"
35. PRICE: "4,900 ₪" big, gold. Under it: "[أو X دفعات]"
36. BONUS: "🎁 لأول [10] بيسجّلوا خلال [30] دقيقة" + "[البونص]". Include a live countdown timer (default 30:00) that starts when this slide is first shown, and a seat counter "[10] مقاعد" that I can decrease with the "-" key.
37. URGENCY: "المقاعد محدودة: [عدد] مقعد · التسجيل بيسكّر [تاريخ ووقت]"
38. CTA: "الرابط بالشات 👇" + the link [LINK] in huge text + a QR code generated from the link
39. UNLOCK slide: "الصفقة اللي أخدتها الأسبوع الماضي 🔓" + chart image placeholder with the 3 parts marked
40. "أسئلة؟ اكتبوها بالشات 👇" — keep the CTA link and QR small in the corner
41. CLOSING: "الفرق بيني وبينك هلأ هو قرار واحد." + link + QR

DATA
- Keep all slide content in one editable file (src/slides.ts) so I can change text, images, and notes easily.
- Image placeholders should be clearly labeled boxes I can replace by uploading an image.
- Add a simple settings panel (press "S") where I can edit: presenter name, strategy name, the 3 parts, price, bonus, seat count, deadline, start date, and the sign-up link. These values fill all slides automatically.

No backend or login needed. It must work offline once loaded.
```
