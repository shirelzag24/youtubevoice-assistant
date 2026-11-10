<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Privacy Policy · YouTube Voice Assistant · מדיניות פרטיות</title>
<!--
  TO DO BEFORE PUBLISHING (delete this comment afterwards):
  1. Replace every highlighted placeholder: [YOUR NAME] and [CONTACT EMAIL] (search for "YOUR NAME" and "CONTACT EMAIL" / "שם המפתחת" and "כתובת מייל").
  2. Check Umami's current privacy policy and make sure section 5 still describes how Umami handles request data.
  3. Update the "Last updated" date whenever the extension's data practices change.
  4. Have the text reviewed by someone qualified if you need legal certainty. This is a draft, not legal advice.
-->
<style>
  :root {
    --bg: #fbfbfa; --text: #1c1d21; --muted: #5a5e69; --rule: #d9dbe1;
    --link: #1a56c4; --mark-bg: #fff2b3; --mark-text: #3b2f00; --band: #eef1f7;
  }
  @media (prefers-color-scheme: dark) {
    :root { --bg: #16181d; --text: #e8e9ee; --muted: #a2a6b2; --rule: #343843;
            --link: #8db4ff; --mark-bg: #4a3d00; --mark-text: #ffe9a1; --band: #20242c; }
  }
  * { box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  @media (prefers-reduced-motion: reduce) { html { scroll-behavior: auto; } }
  body {
    margin: 0; background: var(--bg); color: var(--text);
    font: 17px/1.7 system-ui, -apple-system, "Segoe UI", Roboto, Arial, "Noto Sans Hebrew", "Noto Sans", sans-serif;
  }
  a { color: var(--link); }
  a:focus-visible { outline: 3px solid var(--link); outline-offset: 2px; border-radius: 2px; }
  header.top { background: var(--band); border-bottom: 1px solid var(--rule); }
  .wrap { max-width: 44rem; margin: 0 auto; padding: 0 1.25rem; }
  header.top .wrap { display: flex; flex-wrap: wrap; gap: .5rem 1.5rem; align-items: baseline; justify-content: space-between; padding-top: 1rem; padding-bottom: 1rem; }
  header.top strong { font-size: 1.05rem; }
  nav a { margin-inline-end: 1rem; font-weight: 600; }
  section.doc { padding: 2.5rem 0 3rem; border-bottom: 1px solid var(--rule); scroll-margin-top: 1rem; }
  section.doc:last-of-type { border-bottom: 0; }
  h1 { font-size: 1.9rem; line-height: 1.25; margin: 0 0 .4rem; }
  h2 { font-size: 1.2rem; line-height: 1.35; margin: 2.2rem 0 .5rem; }
  p, li { max-width: 68ch; }
  ul { padding-inline-start: 1.4rem; }
  li { margin: .3rem 0; }
  .meta { color: var(--muted); margin: 0 0 1.5rem; }
  .summary { background: var(--band); border-inline-start: 4px solid var(--link); padding: .9rem 1.1rem; margin: 1.5rem 0; border-radius: 4px; }
  .summary p { margin: .3rem 0; }
  mark { background: var(--mark-bg); color: var(--mark-text); padding: 0 .25em; border-radius: 3px; }
  code { font: .92em/1.4 ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; background: var(--band); padding: .1em .35em; border-radius: 3px; }
  footer { color: var(--muted); font-size: .9rem; padding: 1.5rem 0 3rem; }
</style>
</head>
<body>

<header class="top">
  <div class="wrap">
    <strong>YouTube Voice Assistant</strong>
    <nav aria-label="Language / שפה">
      <a href="#en" hreflang="en">English</a>
      <a href="#he" hreflang="he">עברית</a>
    </nav>
  </div>
</header>

<main>

<!-- ───────────────────────── ENGLISH ───────────────────────── -->
<section class="doc" id="en" lang="en" dir="ltr">
  <div class="wrap">
    <h1>Privacy Policy</h1>
    <p class="meta">YouTube Voice Assistant (Chrome extension) · Last updated: 10 November 2026</p>

    <div class="summary" role="note">
      <p><strong>In short:</strong> the extension listens only to run your voice commands on YouTube. It does not record or send your voice, and it never sends what you said, the songs you search for, or any link to the developer. It reports anonymous counts of which type of action was used, so the developer can improve the extension.</p>
    </div>

    <p>This policy is published by <mark>[YOUR NAME]</mark> (“the developer”, “we”). Contact: <mark>[CONTACT EMAIL]</mark>.</p>

    <h2>1. What the extension does</h2>
    <p>YouTube Voice Assistant lets you control YouTube with your voice, hands-free: pause and resume, rewind and fast-forward, go to a time in the video, skip ads, move to the next or previous song, change volume, speed, subtitles and full screen, and play a song or video by name. It works only on YouTube pages (<code>youtube.com</code> and its subdomains).</p>

    <h2>2. Voice and microphone</h2>
    <ul>
      <li>When you say the wake phrase (for example “Hey YouTube”) or press the microphone button in the player, the extension uses your browser’s built-in speech recognition. Chrome asks for your permission to use the microphone, and you can withdraw it at any time in the browser’s settings.</li>
      <li>Speech recognition is performed by the browser’s speech service (in Chrome this is provided by Google) and is subject to Google’s privacy terms. The extension itself does not record, store or send your audio, and the developer never receives audio or transcripts.</li>
      <li>The extension reads the recognized text only inside your browser, to decide which command to run. When the assistant asks a clarifying question, it may read it aloud with your browser’s text-to-speech voices. Some voices may be provided online by your browser or operating system.</li>
    </ul>

    <h2>3. Information kept on your device</h2>
    <ul>
      <li>Small settings stored in YouTube’s local storage in your browser: your preferred listening languages and whether the welcome tip was already shown.</li>
      <li>When a voice search needs a page reload, the search phrase is kept briefly in your browser’s session storage and is deleted as soon as it is used (and in any case when the tab is closed). It stays on your device.</li>
    </ul>

    <h2>4. Voice search for songs and videos</h2>
    <p>When you ask to play a song or video, the extension enters the phrase into YouTube’s own search and opens a result. That search is handled by YouTube and Google like any search you type there, under their terms. The developer does not receive it.</p>

    <h2>5. Anonymous usage statistics</h2>
    <p>The extension sends a small number of anonymous events to the developer through <strong>Umami</strong> (cloud.umami.is), a web analytics service that processes them on the developer’s behalf:</p>
    <ul>
      <li>that the extension was installed or updated;</li>
      <li>that a YouTube video page was opened (without the address, title or video identifier);</li>
      <li>which <em>type</em> of action ran, for example “pause”, “next song”, “skip ad” or “search” (without what you said or searched for);</li>
      <li>the speech language code in use (for example <code>he-IL</code>), the steps of a clarifying question (asked, yes, no), and a count of commands that were not understood;</li>
      <li>the extension version and your browser’s interface language.</li>
    </ul>
    <p><strong>Never sent:</strong> your voice or audio, what you said, search phrases or song names, links or video identifiers, your account, name, email or any other personal information.</p>
    <p>Like any web service, Umami’s servers receive technical request information such as an IP address and browser type. We use only aggregated statistics (for example counts by country, browser and language). Umami’s own privacy policy applies to how it handles this. The extension does not create user accounts, advertising identifiers or any persistent identifier of its own.</p>

    <h2>6. What we do not do</h2>
    <ul>
      <li>We do not sell user data and we do not use it for advertising or for credit or lending decisions.</li>
      <li>We do not use or transfer user data for purposes unrelated to the extension’s single purpose (voice control of YouTube).</li>
      <li>We share data only with Umami as our analytics service provider, and where the law requires it.</li>
      <li>The use of information received complies with the Chrome Web Store User Data Policy, including its Limited Use requirements.</li>
    </ul>

    <h2>7. Permissions</h2>
    <p>The extension needs access to YouTube pages only (<code>youtube.com</code> and its subdomains), to find the video player and control it (play, pause, seek, volume, speed, subtitles, full screen, skipping ads, moving between videos and running a search). It does not read other websites, and it does not request permissions for tabs, history, cookies or accounts. It does not download or run remote code.</p>

    <h2>8. Your choices</h2>
    <ul>
      <li>You can stop all reporting by uninstalling the extension, and you can turn off the microphone permission at any time.</li>
      <li>Advanced users can stop the usage reports about commands by setting <code>localStorage.ytVoiceAnalytics = '0'</code> on youtube.com, and stop read-aloud questions with <code>localStorage.ytVoiceSpeak = '0'</code>.</li>
      <li>We keep no information that identifies you. If you have a question about your data or want to ask us to delete anything related to you, write to <mark>[CONTACT EMAIL]</mark>.</li>
    </ul>

    <h2>9. Changes to this policy</h2>
    <p>If the extension’s data practices change, we will update this page and its “Last updated” date before the new version is released.</p>

    <h2>10. Contact</h2>
    <p><mark>[YOUR NAME]</mark> · <mark>[CONTACT EMAIL]</mark></p>
  </div>
</section>

<!-- ───────────────────────── עברית ───────────────────────── -->
<section class="doc" id="he" lang="he" dir="rtl">
  <div class="wrap">
    <h1>מדיניות פרטיות</h1>
    <p class="meta">YouTube Voice Assistant (תוסף ל-Chrome) · עודכן לאחרונה: 10 בנובמבר 2026</p>

    <div class="summary" role="note">
      <p><strong>בקצרה:</strong> התוסף מאזין רק כדי לבצע את הפקודות הקוליות שלך ביוטיוב. הוא לא מקליט ולא שולח את הקול שלך, ואף פעם לא שולח למפתחת מה אמרת, אילו שירים חיפשת או קישורים. הוא מדווח ספירות אנונימיות של סוגי פעולות, כדי שאפשר יהיה לשפר אותו.</p>
    </div>

    <p>מדיניות זו מפורסמת על ידי <mark>[שם המפתחת]</mark> (״המפתחת״, ״אנחנו״). ליצירת קשר: <mark>[כתובת מייל]</mark>.</p>

    <h2>1. מה התוסף עושה</h2>
    <p>YouTube Voice Assistant מאפשר לשלוט ביוטיוב בקול, בלי ידיים: עצירה והמשך, הרצה אחורה וקדימה, מעבר לזמן מסוים בסרטון, דילוג על פרסומות, מעבר לשיר הבא או הקודם, שינוי עוצמה, מהירות, כתוביות ומסך מלא, וניגון שיר או סרטון לפי שם. התוסף פועל רק בדפי יוטיוב (<code dir="ltr">youtube.com</code> ותתי-הדומיינים שלו).</p>

    <h2>2. קול ומיקרופון</h2>
    <ul>
      <li>כשאומרים את מילת ההפעלה (למשל ״היי יוטיוב״) או לוחצים על כפתור המיקרופון בנגן, התוסף משתמש בזיהוי הדיבור המובנה של הדפדפן. Chrome מבקש ממך הרשאה להשתמש במיקרופון, ואפשר לבטל אותה בכל עת בהגדרות הדפדפן.</li>
      <li>זיהוי הדיבור מתבצע בשירות הדיבור של הדפדפן (ב-Chrome הוא מסופק על ידי Google) וכפוף לתנאי הפרטיות של Google. התוסף עצמו לא מקליט, לא שומר ולא שולח את האודיו שלך, והמפתחת אף פעם לא מקבלת אודיו או תמלולים.</li>
      <li>התוסף קורא את הטקסט שזוהה רק בתוך הדפדפן שלך, כדי להחליט איזו פקודה לבצע. כשהעוזר שואל שאלת הבהרה, ייתכן שהוא יקריא אותה בקול הקראה של הדפדפן. חלק מהקולות עשויים להיות מסופקים אונליין על ידי הדפדפן או מערכת ההפעלה.</li>
    </ul>

    <h2>3. מידע שנשמר במכשיר שלך</h2>
    <ul>
      <li>הגדרות קטנות באחסון המקומי של יוטיוב בדפדפן שלך: שפות ההאזנה המועדפות עליך, והאם כבר הוצגה הודעת הפתיחה.</li>
      <li>כשחיפוש קולי דורש טעינה מחדש של הדף, משפט החיפוש נשמר לזמן קצר באחסון הסשן של הדפדפן, ונמחק מיד אחרי השימוש (ובכל מקרה כשסוגרים את הלשונית). הוא נשאר במכשיר שלך.</li>
    </ul>

    <h2>4. חיפוש קולי של שירים וסרטונים</h2>
    <p>כשמבקשים לנגן שיר או סרטון, התוסף מקליד את הביטוי בחיפוש של יוטיוב עצמה ופותח תוצאה. החיפוש הזה מטופל על ידי יוטיוב ו-Google כמו כל חיפוש שמקלידים שם, לפי התנאים שלהן. המפתחת לא מקבלת אותו.</p>

    <h2>5. סטטיסטיקות שימוש אנונימיות</h2>
    <p>התוסף שולח למפתחת מספר קטן של אירועים אנונימיים דרך <strong>Umami</strong> (cloud.umami.is), שירות אנליטיקה שמעבד אותם בשם המפתחת:</p>
    <ul>
      <li>שהתוסף הותקן או עודכן;</li>
      <li>שנפתח דף סרטון ביוטיוב (בלי כתובת, כותרת או מזהה הסרטון);</li>
      <li>איזה <em>סוג</em> פעולה בוצע, למשל ״עצירה״, ״שיר הבא״, ״דילוג על פרסומת״ או ״חיפוש״ (בלי מה שנאמר או חיפשת);</li>
      <li>קוד שפת הדיבור שבשימוש (למשל <code dir="ltr">he-IL</code>), שלבי שאלת הבהרה (נשאלה, כן, לא), וספירה של פקודות שלא הובנו;</li>
      <li>גרסת התוסף ושפת הממשק של הדפדפן.</li>
    </ul>
    <p><strong>לעולם לא נשלחים:</strong> הקול או האודיו שלך, מה שאמרת, משפטי חיפוש או שמות שירים, קישורים או מזהי סרטונים, החשבון שלך, שמך, המייל שלך או כל מידע אישי אחר.</p>
    <p>כמו בכל שירות אינטרנט, השרתים של Umami מקבלים מידע טכני על הבקשה, כמו כתובת IP וסוג הדפדפן. אנחנו משתמשים רק בסטטיסטיקות מצטברות (למשל ספירות לפי מדינה, דפדפן ושפה). מדיניות הפרטיות של Umami חלה על אופן הטיפול שלה במידע הזה. התוסף לא יוצר חשבונות משתמש, מזהי פרסום או מזהה קבוע משלו.</p>

    <h2>6. מה אנחנו לא עושות</h2>
    <ul>
      <li>אנחנו לא מוכרות מידע על משתמשים ולא משתמשות בו לפרסום או להחלטות אשראי והלוואות.</li>
      <li>אנחנו לא משתמשות במידע על משתמשים ולא מעבירות אותו למטרות שאינן קשורות למטרה היחידה של התוסף (שליטה קולית ביוטיוב).</li>
      <li>אנחנו משתפות מידע רק עם Umami כספקית האנליטיקה שלנו, ובמקרים שהחוק מחייב.</li>
      <li>השימוש במידע שמתקבל עומד במדיניות הנתונים של חנות Chrome, כולל דרישות ה-Limited Use.</li>
    </ul>

    <h2>7. הרשאות</h2>
    <p>התוסף זקוק לגישה לדפי יוטיוב בלבד (<code dir="ltr">youtube.com</code> ותתי-הדומיינים שלו), כדי למצוא את נגן הסרטונים ולשלוט בו (ניגון, עצירה, מעבר בזמן, עוצמה, מהירות, כתוביות, מסך מלא, דילוג על פרסומות, מעבר בין סרטונים והרצת חיפוש). הוא לא קורא אתרים אחרים, ולא מבקש הרשאות ללשוניות, להיסטוריה, לעוגיות או לחשבונות. הוא לא מוריד ולא מריץ קוד מרוחק.</p>

    <h2>8. הבחירות שלך</h2>
    <ul>
      <li>אפשר להפסיק את כל הדיווח על ידי הסרת התוסף, ואפשר לכבות את הרשאת המיקרופון בכל עת.</li>
      <li>משתמשים מתקדמים יכולים להפסיק את דיווחי השימוש על פקודות באמצעות הגדרת <code dir="ltr">localStorage.ytVoiceAnalytics = '0'</code> ביוטיוב, ולהפסיק שאלות מוקראות עם <code dir="ltr">localStorage.ytVoiceSpeak = '0'</code>.</li>
      <li>אנחנו לא שומרות מידע שמזהה אותך. אם יש לך שאלה על המידע שלך או שאת רוצה לבקש מחיקה של משהו שקשור אלייך, כתבי ל-<mark>[כתובת מייל]</mark>.</li>
    </ul>

    <h2>9. שינויים במדיניות</h2>
    <p>אם הפרקטיקות של התוסף לגבי מידע ישתנו, נעדכן את העמוד הזה ואת תאריך ״עודכן לאחרונה״ לפני שחרור הגרסה החדשה.</p>

    <h2>10. יצירת קשר</h2>
    <p><mark>[שם המפתחת]</mark> · <mark>[כתובת מייל]</mark></p>
  </div>
</section>

</main>

<footer>
  <div class="wrap">Privacy Policy · מדיניות פרטיות — YouTube Voice Assistant</div>
</footer>

</body>
</html>
