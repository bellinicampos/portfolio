title = "Notre-Dame de Paris"
baseURL = "https://example.com"
languageCode = "en-us"
theme = "ananke"
themesDir = "../.."
#resourceDir = "../resources"

DefaultContentLanguage = "en"
SectionPagesMenu = "main"
Paginate = 3 # this is set low for demonstrating with dummy content. Set to a higher number
googleAnalytics = ""
enableRobotsTXT = true

[languages]
  [languages.en]
    title = "My blog"
    weight = 1
    contentDir = "content/en"
  [languages.fr]
    title = "Mon blogue"
    weight = 2
    contentDir = "content/fr"

[sitemap]
  changefreq = "monthly"
  priority = 0.5
  filename = "sitemap.xml"

[params]
  favicon = ""
  site_logo = ""
  description = "The last theme you'll ever need. Maybe."
  facebook = ""
  twitter = "https://twitter.com/GoHugoIO"
  instagram = ""
  youtube = ""
  github = ""
  gitlab = ""
  linkedin = ""
  mastodon = ""
  slack = ""
  stackoverflow = ""
  rss = ""
  # choose a background color from any on this page: http://tachyons.io/docs/themes/skins/ and preface it with "bg-"
  background_color_class = "bg-black"
  featured_image = "/images/gohugo-default-sample-hero-image.jpg"
  recent_posts_number = 2
