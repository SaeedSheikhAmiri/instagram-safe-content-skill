# Instagram Safe Content (Claude skill)

A Claude skill that checks Instagram posts, Reels, Stories, captions, DMs and auto-publishing against Meta's **official** rules before you publish, so content doesn't get removed, lose recommendation to non-followers, or put the account at risk.

Every rule is tagged by weight: **REMOVED**, **NOT RECOMMENDED**, **REQUIRED**, **LIMIT** or **CAUTION** (widely reported but not an official rule). Sources are listed at the bottom of `SKILL.md`. Last checked 2026-11-02.

## What it covers
- Recommendation Guidelines (Explore, Reels, suggested posts) and the under-18 restriction on diet and cosmetic content
- Engagement bait (vote, react, share, tag and comment baiting)
- Spam, fake engagement, Terms of Use
- 5-hashtag limit
- AI label requirement for realistic AI video or voice
- Paid partnership (branded content) label
- Music and copyright for business accounts
- Health and finance claims
- DM automation rules (24-hour window, one private reply per comment within 7 days)
- Content Publishing API limits
- A 14-point pre-publish checklist and a short report format

## Install
- **Claude (claude.ai / desktop):** download `instagram-safe-content.zip` from Releases (or zip the `instagram-safe-content` folder) and upload it under Settings, Capabilities, Skills.
- **Claude Code:** copy the `instagram-safe-content` folder into `~/.claude/skills/`.

Then ask: "Check this caption with instagram-safe-content".

## فارسی
این اسکیل قبل از انتشار، پست، ریلز، استوری، کپشن، دایرکت و انتشار خودکار رو با قوانین رسمی Meta و اینستاگرام چک می‌کنه تا محتوا حذف نشه، از پیشنهاد به غیرفالوورها نیفته و پیج در خطر نباشه. هر قانون منبع رسمی داره و مواردی که فقط تجربه‌ی کاربرهاست جدا علامت خورده.

## Made by
**Saeed SheikhAmiri**, in collaboration with the team behind **[Storya](https://storyainsta.ir)**: a Persian tool that schedules Instagram Stories, posts and Reels through the official Instagram API and publishes them on time. Shared free for anyone who publishes on Instagram.

ساخته‌ی سعید شیخ‌امیری، با همکاری تیم استوریا (StoryaInsta.ir)، ابزار زمان‌بندی و انتشار خودکار استوری، پست و ریلز با API رسمی اینستاگرام.

## License
MIT. Rules change often: verify against the linked official pages before relying on them.
