<!-- ═══════════════════════════════════════════════════════════════ -->
<!--              CONTRIBUTING — SQL Server Book                    -->
<!--              Author: Leo (here-is-leo)                         -->
<!--              Version: 1.0.0                                    -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24&height=140&section=header&text=Contributing&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=55&desc=SQL%20Server%20Book%20%E2%80%94%20Bilingual%20Guide&descAlignY=80&descSize=18" width="100%"/>

<br>

[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](https://github.com/here-is-leo/sqlserver-book/pulls)
[![Made with Love](https://img.shields.io/badge/Made_with-❤️-red?style=for-the-badge)](https://github.com/here-is-leo/sqlserver-book)
[![Contributors](https://img.shields.io/badge/Contributors-Welcome-blue?style=for-the-badge)](https://github.com/here-is-leo/sqlserver-book/graphs/contributors)
[![Code of Conduct](https://img.shields.io/badge/Code_of_Conduct-2.1-purple?style=for-the-badge)](CODE_OF_CONDUCT.md)

**Thank you for considering contributing to this project! 💙**

*از اینکه می‌خواهی به این پروژه کمک کنی، صمیمانه سپاسگزاریم!*

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    TABLE OF CONTENTS                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📋 Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [Ways to Contribute](#-ways-to-contribute)
- [Quick Start](#-quick-start)
- [Git Workflow](#-git-workflow)
- [Code Style](#-code-style)
- [Commit Style](#-commit-style)
- [Pull Request Process](#-pull-request-process)
- [Bug Reports](#-bug-reports)
- [Feature Requests](#-feature-requests)
- [Content Fixes](#-content-fixes)
- [Translation](#-translation)
- [Review Process](#-review-process)
- [Recognition](#-recognition)
- [Contact](#-contact)

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    CODE OF CONDUCT                             -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📜 Code of Conduct

We are committed to providing a **friendly, safe, and harassment-free** environment for all contributors — regardless of nationality, age, gender identity, experience level, religion, or physical ability.

### ✅ Expected Behavior

- 🤝 **Mutual respect** — Treat everyone with respect
- 💬 **Constructive criticism** — Focus on ideas, not people
- 🙏 **Openness to feedback** — See feedback as a learning opportunity
- 🎯 **Focus on the project** — Keep discussions relevant
- 🌱 **Help newcomers** — Mentor beginners

### ❌ Unacceptable Behavior

- 🚫 Insults, derogatory comments, or personal attacks
- 🚫 Discriminatory or racist content
- 🚫 Sexual harassment
- 🚫 Publishing others' private information
- 🚫 Spam and unsolicited promotion

### ⚠️ Consequences

Violations may result in:

1. **Written warning** for the first offense
2. **Temporary ban** for repeated offenses
3. **Permanent ban** for serious violations

**Report violations to:** ilyafarahanii@gmail.com

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    WAYS TO CONTRIBUTE                          -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🌟 Ways to Contribute

You can contribute in **any way** you like:

| # | Contribution Type | Difficulty | Impact |
|---|-------------------|------------|--------|
| 1 | 🐛 Report a bug | 🟢 Easy | ⭐⭐⭐ |
| 2 | ✏️ Fix a typo | 🟢 Easy | ⭐⭐ |
| 3 | 📝 Improve translation | 🟡 Medium | ⭐⭐⭐⭐ |
| 4 | 📚 Add a T-SQL example | 🟡 Medium | ⭐⭐⭐⭐ |
| 5 | 🎨 Improve UI/UX | 🟡 Medium | ⭐⭐⭐ |
| 6 | 🌍 Translate to a new language | 🔴 Hard | ⭐⭐⭐⭐⭐ |
| 7 | 📖 Write a new chapter | 🔴 Hard | ⭐⭐⭐⭐⭐ |
| 8 | ⚡ Performance optimization | 🔴 Hard | ⭐⭐⭐⭐ |
| 9 | 🧪 Write tests | 🟡 Medium | ⭐⭐⭐ |
| 10 | 🔗 Check for broken links | 🟢 Easy | ⭐⭐ |

> **No contribution is too small.** Even fixing a single typo is valuable!

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    QUICK START                                 -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🚀 Quick Start

### Step 1: Fork the Repository

Click the **`Fork`** button at the top-right of the GitHub page. This creates a copy of the repository in your own account.

### Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/sqlserver-book.git
cd sqlserver-book
💡 Replace YOUR-USERNAME with your actual GitHub username.

Step 3: Add Upstream Remote
bash
git remote add upstream https://github.com/here-is-leo/sqlserver-book.git
git remote -v
Step 4: Create a New Branch
bash
git checkout -b feature/your-feature-name
Step 5: Make Your Changes
Edit index.html or README.md, or add new files.

Step 6: Test Locally
bash
# Open in browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
Verify that:

✅ Both Persian and English work

✅ Dark and light themes are intact

✅ Mobile and desktop display correctly

✅ Keyboard navigation works (arrow keys)

✅ No errors in browser console (F12)

Step 7: Commit
bash
git add .
git commit -m "feat: add new section about X"
Step 8: Push
bash
git push origin feature/your-feature-name
Step 9: Open a Pull Request
Go to your fork on GitHub and click the Compare & pull request button.

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- GIT WORKFLOW <--<!-- ═══════════════════════════════════════════════════════════════ <--
🌿 Git Workflow
We use a lightweight Git Flow model:

Branch	Purpose	Color
main	Production — stable	🟢
develop	Development — experimental	🟡
feature/*	New feature	🔵
fix/*	Bug fix	🔴
docs/*	Documentation	🟣
content/*	Educational content	🟠
i18n/*	Translation	🟤
✅ Good Branch Names
bash
feature/add-window-functions
feature/search-functionality
fix/dark-mode-safari
fix/rtl-code-blocks
docs/update-readme
content/join-examples
i18n/add-arabic-translation
❌ Bad Branch Names
bash
my-branch
test
asdf
update
new-stuff
temp
🔄 Syncing with Upstream
Keep your fork up to date:

bash
# Fetch latest from upstream
git fetch upstream

# Switch to main
git checkout main

# Merge upstream changes
git merge upstream/main

# Return to your branch
git checkout feature/your-feature

# Rebase to apply your changes on top
git rebase main
<!-- ═══════════════════════════════════════════════════════════════ <--<!-- CODE STYLE <--<!-- ═══════════════════════════════════════════════════════════════ <--
🎨 Code Style
General Rules
Item	Value
Indentation	2 spaces (not Tab)
Quotes in JS	Double quotes "like this"
Line ending	LF (not CRLF)
Max line length	120 characters
CSS class naming	kebab-case (page-content)
JS variable naming	camelCase (currentPage)
JS constants	UPPER_SNAKE_CASE (MAX_PAGES)
HTML attributes	Double quotes
Comments	English or Persian both OK
✅ Good HTML Example
html
<article class="page-content">
  <h1>Page Title</h1>
  <p>
    This is a sample paragraph with
    <strong>important text</strong>.
  </p>
  <div class="code-block">
    <span class="keyword">SELECT</span> *
    <span class="keyword">FROM</span> Users;
  </div>
</article>
✅ Good CSS Example
css
.page-content {
  padding: 20px;
  background: var(--surface);
  border-radius: 12px;
  transition: background 0.3s ease;
}

.page-content h1 {
  color: var(--text);
  font-size: 2rem;
  line-height: 1.2;
}
✅ Good JavaScript Example
javascript
const MAX_PAGES = 51;
let currentPage = 0;

function goToPage(index) {
  if (index < 0 || index >= MAX_PAGES) return;

  currentPage = index;
  renderPage();
  updateProgress();
}
🎨 CSS Variables
Always use CSS variables instead of hardcoded colors:

css
/* ✅ Good */
color: var(--text);
background: var(--accent);

/* ❌ Bad */
color: #1a1a2e;
background: #354AC4;
📱 Responsive Design
Always test your changes on:

📱 Mobile (375px width)

📱 Tablet (768px width)

💻 Desktop (1440px width)

♿ Accessibility
Ensure your changes:

Have proper aria-label attributes

Support keyboard navigation

Have sufficient color contrast (WCAG AA)

Work with screen readers

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- COMMIT STYLE <--<!-- ═══════════════════════════════════════════════════════════════ <--
📝 Commit Style
We follow Conventional Commits:

text
<type>(<scope>): <subject>

<body>

<footer>
Commit Types
Type	Purpose	Example
feat	New feature	feat(search): add full-text search
fix	Bug fix	fix(theme): dark mode on Safari
docs	Documentation	docs(readme): update screenshots
style	Formatting, no logic change	style(css): fix indentation
refactor	Code rewrite	refactor(app): simplify routing
perf	Performance	perf(render): lazy load pages
test	Add tests	test(nav): add keyboard tests
chore	Maintenance	chore(deps): update fonts
content	Educational content	content(join): add anti-join example
i18n	Translation	i18n(fa): improve Persian typography
revert	Revert a change	revert: undo theme change
✅ Good Examples
text
feat(search): add full-text search across pages
fix(rtl): correct code block direction in Persian
docs(readme): add preview screenshots
content(window): add LAG/LEAD examples
i18n(fa): fix ZWNJ in section titles
perf(theme): cache theme preference
style(css): use CSS variables in new sections
❌ Bad Examples
text
update stuff          ← vague
fix bug               ← which bug?
new feature           ← what feature?
asdfgh                ← meaningless
WIP                   ← work in progress
final                 ← meaningless
changes               ← meaningless
📝 Multi-line Commits
For large changes, use the body:

text
feat(search): add full-text search across pages

- Add search input to header
- Implement fuzzy matching with Fuse.js
- Support both Persian and English search
- Add keyboard shortcut Ctrl+K
- Save recent searches to localStorage

Closes #42
🔗 Linking Issues
Use these keywords in your commit or PR to auto-close issues:

Closes #123

Fixes #123

Resolves #123

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- PULL REQUEST PROCESS <--<!-- ═══════════════════════════════════════════════════════════════ <--
🔄 Pull Request Process
Pre-PR Checklist
Before opening a PR, verify:

□ Code tested in browser
□ Tested on mobile (DevTools ← Responsive Mode)
□ Both Persian and English work
□ Dark and light themes intact
□ Tested in Chrome, Firefox, and Safari
□ Changes are focused on the PR topic
□ Commit message follows Conventional Commits
□ Documentation updated (if needed)
□ Link to related Issue in PR description
□ Code is clean and readable
□ No console.log statements left behind
□ No commented-out code
PR Title Format
Use the same format as commits:

text
feat(search): add full-text search
fix(rtl): correct code block direction
docs(readme): add preview screenshots
PR Template
markdown
## 📋 Description
Brief description of changes and why.

## 🔗 Related Issue
Closes #123

## 🧪 Type of Change
- [ ] 🐛 Bug fix
- [ ] ✨ New feature
- [ ] 📝 Documentation
- [ ] 🎨 UI/UX improvement
- [ ] ⚡ Performance
- [ ] 🌍 Translation
- [ ] 📚 Content addition
- [ ] 🔧 Refactoring

## 📸 Screenshot (if UI change)
| Before | After |
|:------:|:-----:|
| ![before](url) | ![after](url) |

## ✅ Checklist
- [ ] Code tested
- [ ] Docs updated
- [ ] No console errors
- [ ] Mobile-friendly
- [ ] Both languages work
- [ ] Dark/light themes intact

## 📝 Notes for reviewer
Anything reviewer should know.
Review Process
Open PR — wait for review

CI runs — automated checks

Code review — maintainer may request changes

Address feedback — apply changes

Approval — maintainer approves

Merge — merged into main

⏱️ Expected Wait Times
⏱️ 24-48 hours — initial response

⏱️ 3-7 days — full review

⏱️ Varies — depends on PR complexity

🔧 If Your PR Fails CI
bash
# 1. Get upstream changes
git fetch upstream
git rebase upstream/main

# 2. Resolve conflicts manually
# (edit conflicting files)

# 3. Continue the rebase
git add .
git rebase --continue

# 4. Push (force-with-lease is safer)
git push --force-with-lease origin feature/your-feature
🚫 What Gets PRs Rejected
❌ Hardcoded colors instead of CSS variables

❌ Breaking existing features

❌ Not testing both languages

❌ Not testing dark/light themes

❌ Large unrelated changes in one PR

❌ Ignoring maintainer feedback

❌ Adding external dependencies without discussion

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- BUG REPORTS <--<!-- ═══════════════════════════════════════════════════════════════ <--
🐛 Bug Reports
Before Reporting
🔍 Search existing issues

🔄 Ensure you're on the latest version

🧪 Test in another browser

🧹 Clear browser cache and reload

Information Needed
A good bug report includes:

📝 Clear title — one sentence describing the bug

📋 Steps to reproduce — step-by-step instructions

✅ Expected behavior — what should happen

❌ Current behavior — what actually happens

📸 Screenshot or video — if possible

🌐 Environment — browser, OS, language, theme

📄 Error messages — from browser console (F12)

Bug Report Template
markdown
## 🐛 Bug Description
Clear, concise description of what's wrong.

## 📋 Steps to Reproduce
1. Go to '...'
2. Click on '...'
3. Scroll to '...'
4. See error

## ✅ Expected Behavior
What should happen.

## ❌ Actual Behavior
What actually happens.

## 📸 Screenshot
If applicable, add screenshots.

## 🌐 Environment
- **Browser:** Chrome 120
- **OS:** Windows 11
- **Language:** Persian / English
- **Theme:** Light / Dark
- **Page:** Page number where bug occurs

## 📄 Console Errors
Paste any errors from browser console (F12).
Use the Issue Template
Go to Issues ← New Issue and select Bug Report.

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- FEATURE REQUESTS <--<!-- ═══════════════════════════════════════════════════════════════ <--
💡 Feature Requests
Before Suggesting
🔍 Search existing issues

📖 Check the ROADMAP

🤔 Ensure it aligns with the project's goals

💭 Think about implementation

Structure Your Suggestion
🎯 Problem — What problem are you facing?

💡 Solution — What solution do you propose?

🔄 Alternatives — What other approaches did you consider?

📚 Examples — For educational features, list headings

🎨 Visual mockup — If UI-related, add a sketch or description

Feature Request Template
markdown
## 🎯 Problem
What problem does this solve?

## 💡 Proposed Solution
How would you like it to work?

## 🔄 Alternatives Considered
What other solutions did you consider?

## 📚 Content Outline (if educational)
- Topic 1
- Topic 2
- Topic 3

## 📸 Visual Mockup (if UI)
Sketch or description of the UI.

## 📝 Additional Context
Anything else relevant.
Use the Issue Template
Go to Issues ← New Issue and select Feature Request.

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- CONTENT FIXES <--<!-- ═══════════════════════════════════════════════════════════════ <--
✏️ Content Fixes
Content improvements are always welcome — from typo fixes to technical corrections.

Types of Content Fixes
Type	Example	How to Submit
🔤 Typo fix	teh → the	Direct PR (small)
📝 Grammar	Rewording awkward sentences	Direct PR (small)
🎯 Technical error	Wrong T-SQL syntax	Issue first, then PR
📚 Missing example	Adding a new query example	Issue first, then PR
📖 New chapter	Adding a whole new section	Issue first, then PR
🗺️ Structure	Reorganizing content	Issue first, then PR
Guidelines for Content
✅ Accuracy first — Verify T-SQL on real SQL Server

✅ Both languages — Update both contentFa and contentEn

✅ Consistent style — Match existing tone and format

✅ Real examples — Use runnable code, not pseudocode

✅ Cited sources — Link to Microsoft Learn for technical claims

✅ Version notes — Mention SQL Server version when relevant

T-SQL Code Standards
sql
-- ✅ Good: readable, commented, formatted
SELECT 
    CustomerID,
    OrderDate,
    TotalDue
FROM Sales.Orders
WHERE OrderDate >= '2026-01-01'
  AND CustomerID = 42;

-- ❌ Bad: unreadable, uncommented
select CustomerID,OrderDate,TotalDue from Sales.Orders where OrderDate>='2026-01-01' and CustomerID=42
Content Quality Checklist
□ Technically accurate
□ Tested on real SQL Server
□ Both Persian and English versions updated
□ Typos fixed
□ Formatting consistent with existing content
□ No plagiarism — original writing
□ Sources cited where appropriate
<!-- ═══════════════════════════════════════════════════════════════ <--<!-- TRANSLATION <--<!-- ═══════════════════════════════════════════════════════════════ <--
🌍 Translation
Want to add a new language? Wonderful!

Currently Supported
🇮🇷 Persian (fa) — Primary

🇺🇸 English (en) — Primary

Languages We'd Love
🇸🇦 Arabic (ar)

🇹🇷 Turkish (tr)

🇩🇪 German (de)

🇫🇷 French (fr)

🇪🇸 Spanish (es)

🇷🇺 Russian (ru)

🇨🇳 Chinese (zh)

🇯🇵 Japanese (ja)

How to Add a Language
Open an Issue first to discuss scope

Wait for approval from maintainer

Follow the structure of existing contentFa / contentEn

Keep code blocks LTR even in RTL languages

Use appropriate fonts for the language

Test thoroughly on your device

Submit a PR with the new language

Persian Content Rules
✅ Use Persian ی (not Arabic ي)

✅ Use Persian ک (not Arabic ك)

✅ Use ZWNJ for compound words: می‌شود

✅ Numbers in Persian text: ۱۲۳

✅ Numbers in code: 123 (unchanged)

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- REVIEW PROCESS <--<!-- ═══════════════════════════════════════════════════════════════ <--
👀 Review Process
What Reviewers Look For
Aspect	What's Checked
Correctness	Does it work as described?
Consistency	Does it match existing style?
Completeness	Are both languages updated?
Quality	Is the content accurate and clear?
Performance	Does it slow down the page?
Accessibility	Is it keyboard/screen-reader friendly?
Mobile	Does it work on small screens?
Reviewer Response Times
🟢 Small PRs (typo, small fix) — 1-2 days

🟡 Medium PRs (new example, refactor) — 3-5 days

🔴 Large PRs (new chapter, feature) — 1-2 weeks

What Happens After Review
✅ Approved ← Merged into main

🔄 Changes requested ← Update your PR

❌ Rejected ← Explanation provided

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- RECOGNITION <--<!-- ═══════════════════════════════════════════════════════════════ <--
🏆 Recognition
Every contributor gets credit:

🌟 Listed in Contributors

📝 Mentioned in CHANGELOG.md

💬 Shoutout in release notes

Top Contributors
Contributors with 5+ merged PRs get:

🥇 Listed in README as a "Core Contributor"

🎁 Special mention in release notes

💬 Direct contact with the maintainer

<!-- ═══════════════════════════════════════════════════════════════ <--<!-- CONTACT <--<!-- ═══════════════════════════════════════════════════════════════ <--
📞 Contact
<div align="center">
https://img.shields.io/badge/GitHub-here--is--leo-181717?style=for-the-badge&logo=github&logoColor=white
https://img.shields.io/badge/Website-here--is--leo.ir-354AC4?style=for-the-badge&logo=googlechrome&logoColor=white
https://img.shields.io/badge/Telegram-@Here__is__leo-26A5E4?style=for-the-badge&logo=telegram&logoColor=white
https://img.shields.io/badge/Email-ilyafarahanii@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white

For general questions: Open a Discussion
For security issues: See SECURITY.md

</div>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer&text=Thank%20You!&fontSize=30&fontColor=ffffff&animation=fadeIn" width="100%"/>
🌟 Every Contribution Matters
"Alone we can do so little; together we can do so much."
— Helen Keller

Happy contributing! 🎉

</div>
<!-- ═══════════════════════════════════════════════════════════════ <--<!-- PERSIAN VERSION <--<!-- ═══════════════════════════════════════════════════════════════ <--<div dir="rtl" align="right">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24&height=140&section=header&text=راهنمای%20مشارکت&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=55&desc=کتاب%20جامع%20SQL%20Server&descAlignY=80&descSize=18" width="100%"/>
از اینکه می‌خواهی به این پروژه کمک کنی، صمیمانه سپاسگزاریم! 💙

</div>
<div dir="rtl" align="right">
📋 فهرست مطالب
آیین‌نامه رفتار

راه‌های مشارکت

شروع سریع

گردش کار Git

سبک کد

سبک Commit

فرآیند Pull Request

گزارش باگ

پیشنهاد ویژگی

اصلاح محتوا

ترجمه

فرآیند بازبینی

قدردانی

ارتباط با ما

📜 آیین‌نامه رفتار
ما متعهد به ایجاد محیطی دوستانه، امن، و بدون تبعیض برای همه مشارکت‌کنندگان هستیم — فارغ از ملیت، سن، جنسیت، سطح تجربه، مذهب، یا وضعیت جسمی.

✅ رفتارهای مورد انتظار
🤝 احترام متقابل — با همه با احترام رفتار کنید

💬 نقد سازنده — روی ایده تمرکز کنید، نه فرد

🙏 پذیرش بازخورد — بازخورد را فرصت یادگیری ببینید

🎯 تمرکز بر پروژه — بحث‌ها را مرتبط نگه دارید

🌱 کمک به تازه‌واردها — به مبتدیان کمک کنید

❌ رفتارهای غیرقابل قبول
🚫 توهین، تحقیر، یا حملات شخصی

🚫 محتوای تبعیض‌آمیز یا نژادپرستانه

🚫 آزار و اذیت جنسی

🚫 انتشار اطلاعات خصوصی دیگران

🚫 اسپم و تبلیغات ناخواسته

⚠️ پیامدها
نقض این اصول می‌تواند منجر به:

اخطار کتبی برای اولین تخلف

حذف موقت برای تکرار

بلاک دائمی برای تخلفات جدی

گزارش تخلفات به: ilyafarahanii@gmail.com

🌟 راه‌های مشارکت
شما می‌توانید از هر طریقی که دوست دارید کمک کنید:

#	نوع مشارکت	سطح سختی	تأثیر
۱	🐛 گزارش باگ	🟢 آسان	⭐⭐⭐
۲	✏️ اصلاح غلط تایپی	🟢 آسان	⭐⭐
۳	📝 بهبود ترجمه	🟡 متوسط	⭐⭐⭐⭐
۴	📚 افزودن مثال T-SQL	🟡 متوسط	⭐⭐⭐⭐
۵	🎨 بهبود رابط کاربری	🟡 متوسط	⭐⭐⭐
۶	🌍 ترجمه به زبان دیگر	🔴 سخت	⭐⭐⭐⭐⭐
۷	📖 نوشتن فصل جدید	🔴 سخت	⭐⭐⭐⭐⭐
۸	⚡ بهینه‌سازی کارایی	🔴 سخت	⭐⭐⭐⭐
۹	🧪 نوشتن تست	🟡 متوسط	⭐⭐⭐
۱۰	🔗 بررسی لینک‌های خراب	🟢 آسان	⭐⭐
هیچ مشارکتی کوچک نیست. حتی اصلاح یک غلط تایپی ارزشمند است!
