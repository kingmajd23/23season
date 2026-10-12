# Lovable Prompt v2: Fibonacci Webinar Slides

Paste everything inside the box into Lovable as the first message of a new project.
Matches `06-script-fibonacci.md`.

```
Build a full-screen slide presentation web app for a live trading webinar in spoken Arabic. It will be screen-shared on Zoom, so it must look great at 1920x1080 and stay readable on a phone.

TOPIC
One trading strategy: Fibonacci retracement + support & resistance. The presenter grew an account from 500 ILS to 4,000 ILS in September (700%). The webinar teaches the basics and sells a 90-day program called "90 Stox".

LANGUAGE & DIRECTION
- All slide text is Arabic, RTL (dir="rtl"). Font: "Cairo" (Google Fonts). Headlines 64–96px bold, body 32–40px.
- One idea per slide, very little text.

DESIGN
- Dark premium trading look: background #0B0F14, white text, green #22C55E (wins/support), red #EF4444 (mistakes/resistance), gold #F5B800 (Fibonacci golden zone, the offer, the gift).
- Subtle candlestick pattern in the background at low opacity. Small "90 Stox" logo in a corner.
- Smooth fade transitions. Numbers count up when they appear.

DRAWN CHART VISUALS (build these as animated SVG components, not images)
- A simple candlestick chart component with props for candles, horizontal lines and shaded zones, used on several slides.
- Support line (green) and resistance line (red) drawn across the chart with an animation.
- Fibonacci retracement tool: draw from a swing low to a swing high, then animate horizontal levels appearing one by one: 23.6%, 38.2%, 50%, 61.8%, 78.6%, each labelled.
- "Golden zone": the band between 50% and 61.8% shaded gold and gently pulsing.
- Bounce animation: price candles move down into the golden zone and bounce up.

CONTROLS
- Space, Enter, click, or right-arrow = next. Left-arrow or Backspace = previous.
- F = fullscreen, B = black screen, P = presenter view in a second tab (current slide, next slide, notes, timer; sync via BroadcastChannel). Progress bar at the bottom.
- S = settings panel to edit: presenter name, start balance, end balance, weekly checkpoints, regular price, webinar price, installments, offer deadline, gift text, condition #1 text, payment link, cohort start date. Values fill all slides automatically and are saved in localStorage.

SLIDES (keep the Arabic exactly; [brackets] come from settings or are image placeholders)

1. TITLE: "إستراتيجية وحدة." / "من 500 لـ 4,000 شيكل بشهر" / [اسمك] · 20/10
2. "اكتبولي بالشات من وين انتو" (chat bubble icon)
3. Big number reveal: "500 ₪" with small caption "أول شهر 9" + image placeholder for account screenshot
4. Big number reveal: "4,000 ₪" with caption "آخر شهر 9" + image placeholder for account screenshot
5. "700%" huge, gold, counting up from 0. Caption: "بإستراتيجية وحدة"
6. "الليلة رح تشوف 3 إشياء": three cards: (1) أكبر صفقة بالشهر (lock icon) (2) الشروط اللي بقرّر فيها أدخل (lock icon) (3) هدية للي بضلّوا للآخر (gift icon, lock)
7. "اكتبولي جاهز"
8. "مين أنا؟": "[اسمك]" · "7 سنين بالسوق" + photo placeholder
9. "كل أسبوع إستراتيجية جديدة… كل شهر كورس جديد" (red, chaotic collage of crossed-out words: إنديكيتورز، سكالبينج، أوبشنز، تيليغرام، يوتيوب)
10. Quote: "المشكلة مش إني ما بعرف كفاية. المشكلة إني بعرف كتير، وما متقن ولا إشي."
11. Section title: "الأساسيات"
12. FOOTBALL: "شو بتعلّم الولد بالأول؟" with three green check items: "يمشي بالطابة", "يمرّر باص", "يشوط عالجول" and two red crossed items: "فخ التسلّل", "بايسكل كيك" (football icon)
13. "كل مجال بالحياة: إذا أتقنت الأساسيات، بتصير منيح فيه"
14. "مين بيقدر يبلّش؟": four cards: "ما بهم عمرك", "ما بهم خلفيتك", "حتى لو عمرك ما فتحت شارت", "تبلّش بـ 100–300 دولار"
15. "اكتبولي قديش عمرك"
16. Section title: "الأساس الأول: الدعم والمقاومة"
17. House metaphor: a simple house drawing with "الأرضية = الدعم" (green) and "السقف = المقاومة" (red)
18. Chart component: price bouncing off a green support line 3 times, then off a red resistance line
19. "لما السقف ينكسر… بيصير أرضية" with chart animation of resistance turning into support (red line turns green)
20. Section title: "الأساس التاني: فيبوناتشي"
21. Sequence animating in: "1, 1, 2, 3, 5, 8, 13, 21, 34, 55…" (left-to-right numbers inside RTL layout)
22. "النسبة الذهبية" "0.618" huge gold + caption "كل رقم ÷ الرقم اللي بعده"
23. Nature: three image placeholders "عبّاد الشمس", "الصدفة", "المجرّة" with a golden spiral overlay
24. "السوق ما بيطلع بخط مستقيم": chart showing up, pullback, up
25. Fibonacci levels: chart component drawing the Fibonacci tool from swing low to swing high, levels 23.6 / 38.2 / 50 / 61.8 / 78.6 appearing one by one
26. "ليش بتشتغل؟": "ملايين المتداولين والبنوك بيشوفوا نفس المستويات"
27. "كيف بنرسمها؟": "من أدنى نقطة ← لأعلى نقطة" with animated drawing
28. Section title (gold): "المنطقة الذهبية"
29. Chart: golden zone 50%–61.8% shaded gold, pulsing
30. Chart: golden zone overlapping an old green support line; caption "خطّين بيحكوا نفس الإشي = منطقة قوية"
31. Three mini charts side by side: price bouncing from the overlap each time
32. Cliffhanger: "بس…" then "3 شروط لازم يتحققوا" with three locked cards "شرط 1", "شرط 2", "شرط 3" + "وين الوقف؟ وين الهدف؟" (all locked)
33. Month timeline: start balance → weekly checkpoints → end balance, animated line chart going up (values from settings)
34. "أكبر صفقة بالشهر" unlock animation + image placeholder for the trade chart + "[النتيجة]"
35. Honest disclaimer (calm, smaller text): "هاد شهر واحد ونتيجة حقيقية، بس مش وعد. التداول فيه مخاطرة. اللي بوعدكم فيه: الطريقة والمرافقة."
36. "الهدف مش 700% بشهر. الهدف تتقن إستراتيجية وحدة."
37. "اكتبولي جاهز"
38. "شو ما شرحت الليلة": locked list: "الـ 3 شروط", "وين الوقف والهدف", "قديش تخاطر بكل صفقة", "كيف تطبّقها كل يوم"
39. OFFER TITLE: "90 Stox" huge gold. "90 يوم · إستراتيجية وحدة · تتداول لحالك وبثقة" + "الفوج الجاي: [cohort start]"
40. WHAT YOU GET: checklist appearing one by one: "الإستراتيجية كاملة خطوة بخطوة", "[X] جلسات لايف بالأسبوع", "تداول لايف معي", "مجموعة خاصة ومتابعة يومية", "[extra]"
41. PRICE: regular price "4,900 ₪" crossed out in grey, then webinar price "[webinar price]" big gold, "[installments]" under it, and a live countdown to [offer deadline]
42. GIFT: gift box opening animation → "[gift text]" + "بس للي بيسجلوا الليلة"
43. CTA: "الرابط بالشات" + [payment link] huge + QR code generated from the payment link
44. UNLOCK: "الشرط الأول" → "[condition #1 text]" (cards 2 and 3 stay locked with caption "بنتعلمهم بأول أسبوع بـ 90 Stox")
45. Q&A: "أسئلة؟ اكتبوها بالشات" with payment link + QR small in the corner
46. CLOSING: "السؤال مش إذا بتقدر. السؤال: بدك تبلّش؟" + payment link + QR

DATA
- All slide content and speaker notes in one editable file (src/slides.ts).
- Image placeholders are labelled boxes I can replace by uploading images.
- No backend, no login. Works offline once loaded.
```
