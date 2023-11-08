


# CyberSyn
# CyberSEO Lite
# CyberSEO Lite Plugin
![icon-128x128](https://github.com/sharklatan/CyberSyn/assets/5210221/b71b5f76-9732-4078-9afa-848a2d35fcfc)
![cybersyn-128x128](https://github.com/sharklatan/CyberSyn/assets/5210221/281d974c-3957-43fa-907f-da890d0fa2fd)

CyberSEO Lite is a simplified version of [CyberSEO Pro](http://www.cyberseo.net/) – an advanced yet user-friendly auto-blogging and content curation plugin for WordPress. It allows you to import RSS and Atom feeds and automatically convert the content into WordPress posts on your site. The plugin comes with powerful tools typically found in premium solutions.

https://github.com/sharklatan/CyberSyn/assets/5210221/c21d1c5e-e0cc-4646-86ad-d27d832752ca


At the current moment, CyberSEO Lite is the only open-source freeware plugin capable of extracting full-text articles from shortened feeds, translating articles to/from over 100 languages using Google Translate and Yandex Translate services, and spinning content with 3rd-party content spinners. All these features are free and available after activating the plugin, without any hidden fees or limitations.


https://github.com/sharklatan/CyberSyn/assets/5210221/fbbcafd7-a6db-432b-b67e-a564853019c5


### Key Features:
- Generate WordPress posts from [Atom](http://en.wikipedia.org/wiki/Atom_%28standard%29)/[RSS](http://en.wikipedia.org/wiki/RSS) feeds and automate your site content.
- Spin post content with [WordAI](http://www.cyberseo.net/partners/wordai.php), [SpinnerChief](http://www.cyberseo.net/partners/spinnerchief.php), and [SpinRewriter](https://web.archive.org/web/20200930220735/http://www.cyberseo.net/partners/spinrewriter.php) 3rd-party services.
- Assign a [WPML](https://www.cyberseo.net/partners/wpml.php) language code to generated posts.
- Embed media attachments (images and videos) into the posts.
- Embed videos from YouTube, Vimeo, Flickr, IGN, Ustream.tv, and DailyMotion RSS feeds.
- Generate featured images (post thumbnails) from post images or media attachments.
- Full Text RSS extractor for importing full-text articles.
- Translate syndicated articles from/to more than 100 languages via Yandex Translate and Google Translate services.
- Advanced RSS/Atom parsing algorithm for automatic feed updates.
- Adjustable post duplicate check by GUID, post title, or both.
- Import articles as drafts or publish them immediately.
- Automatically assign post categories and tags.
- Shorten post excerpts by a given length.
- Add custom HTML code (custom footers) to every syndicated post.
- Convert character encoding if the source feed has a non-UTF-8 one.

**Missing some features? Consider upgrading to CyberSEO Pro to add the following advanced features:**
- Import XML feeds of any format into WordPress posts and pages. The internal structure of XML feeds is recognized and parsed automatically.
- Import HTML and JSON sources into WordPress post and pages. The internal structure of JSON sources is recognized and parsed automatically.
- Import pipe-delimiter raw text dumps and Excel-style CSV files into WordPress posts and pages.
- Assign WordPress post format to every post (e.g., Aside, Gallery, Link, Video, Audio, etc.).
- Use the built-in synonymizer to synonymize, spin, and rewrite the syndicating content according to your rules.
- Shuffle paragraphs of the importing articles.
- Simulate any [user agent](https://web.archive.org/web/20200930220735/https://en.wikipedia.org/wiki/User_agent) software.
- Use proxy lists to pull content sources using different IP addresses.
- Create and modify post custom fields on the fly.
- Take advantage of additional 3rd-party content spinners, such as [Espinner](https://web.archive.org/web/20200930220735/https://www.cyberseo.net/partners/espinner.php) and [ChimpRewriter](https://web.archive.org/web/20200930220735/https://www.cyberseo.net/partners/spinchimp.php).
- Import all published posts from any other WordPress site with a single click, regardless of how many recent posts are included in its RSS feed, as the plugin will pull them all.
- Use [post templates](https://web.archive.org/web/20200930220735/http://www.cyberseo.net/content-syndicator/#templates) to define layouts for auto-generated posts and pages.
- Use predefined [presets](https://web.archive.org/web/20200930220735/http://www.cyberseo.net/presets/) from the library and create your own ones! Presets allow you to import various content sources as image galleries, tube videos, full-text articles, etc., with just a couple of mouse clicks!
- Filter articles and other content items according to your rules.
- Hotlink attached post videos or upload them to your host.
- Use [Article Forge](https://web.archive.org/web/20200930220735/http://www.cyberseo.net/partners/articleforge.php) service to automatically generate unique, on-topic, high-quality articles.
- Use the auto-commenting tool to generate comments for the posts. Please note that this is NOT a spamming tool, as it adds comments only to your own site.
- Assign a lifetime period to every post or page.
- Republish existing posts.
- Automatically assign content-related tags.
- Write your own parsing scripts in PHP to alter the syndicating content. With this feature, you gain absolute power over content! This is a truly limitless feature!
- Let CyberSEO update itself automatically.

## Live Demo:
[http://www.manpinner.com/](https://web.archive.org/web/20200930220735/http://www.manpinner.com/)

## Requirements:
- PHP 5.3 or greater
- MySQL 5.0 or greater
- PHP mbstring extension
- PHP cURL extension (recommended)
- Disabled PHP variable safe_mode (if cURL is not installed)
- Enabled PHP variable allow_url_fopen (if cURL is not installed)
- Access to cron on the server (recommended)

To get started:
1. Go to **CyberSEO Lite -> RSS/Atom Syndicator**.
2. Enter the RSS feed URL in the "New Feed URL:" field (e.g., http://rss.cnn.com/rss/cnn_latest.rss) and click "Syndicate".
3. Configure the necessary options (default settings are recommended for beginners).
4. Click "Syndicate This Feed".
5. Select the feed, click the checkbox, and click "Pull selected feeds now!" to import posts to your blog.
