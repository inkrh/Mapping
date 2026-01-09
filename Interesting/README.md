# Interesting data

Several months worth of news story links from a limited set of news feeds for specific keywords continually gathered over a period of around 7 years.


## FeedHistory.db

FeedHistory.db contains searches from 2017 to 2024 for references to:

KeyPhrases= ["climate change","global warming", "environment","climatechange",
             "sea level", "energy","temperature","climate", "species", "smog",
             "pollution","flood","extinct","oil pipe", "extinct", "air quality"]


ExcludedWords = ['clickbait','how can', 'are you', 'asylum seeker', 'what I wore this week','quits crisps','northern ireland assembly','fashion']


On the following feeds:

FeedList = {
    "BBC News":"http://feeds.bbci.co.uk/news/rss.xml",
    "BBC Environment":"http://feeds.bbci.co.uk/news/science_and_environment/rss.xml",
    "BBC World News":"http://feeds.bbci.co.uk/news/world/rss.xml",
    "Google":"http://news.google.com/news?output=rss",
    "BBC UK News":"http://feeds.bbci.co.uk/news/uk/rss.xml",
    "BBC US News":"http://feeds.bbci.co.uk/news/world/us_and_canada/rss.xml",
    "BBC Middle East News":"http://feeds.bbci.co.uk/news/world/middle_east/rss.xml",
    "CNN Top Stories":"http://rss.cnn.com/rss/cnn_topstories.rss",
    "CNN World News":"http://rss.cnn.com/rss/cnn_world.rss",
    "CNN US News":"http://rss.cnn.com/rss/cnn_us.rss",
    "News24":"http://feeds.news24.com/articles/News24/Technology/rss",
    "WWF":"http://feeds.feedburner.com/WWFStories?format=xml",
    "WWF In News":"http://feeds.feedburner.com/WWF-InTheNews?format=xml",
    "Guardian":"http://www.theguardian.com/rss"
    }

## SecurityNews

SecurityNews.db contains searches from 2018 to 2024 for references to:

KeyPhrases= ["security","trojan", "password","security", "vulnerability",
             "android", "ios","protocol", " http ", "virus", "malware", "adware","risk","windows","apple","google","fraud", "banking",
             " hack"]

RequiredWords = ["mobile", " app"]

ExcludedWords =  ['clickbait']



On the following feeds:

FeedList = {
    "BBC News":"http://feeds.bbci.co.uk/news/technology/rss.xml",
    "Wired Security":"https://www.wired.com/feed/category/security/latest/rss",
    "Wired Business":"https://www.wired.com/feed/category/business/latest/rss",
    "CNN Technology":"http://rss.cnn.com/rss/cnn_tech.rss",
    "Google":"http://news.google.com/news?output=rss",
    "Guardian":"https://www.theguardian.com/us/technology/rss",
    "EFF":"https://www.eff.org/rss/updates.xml",
    "Threat Post":"https://threatpost.com/feed/",
    "Dark Reading":"https://www.darkreading.com/rss_simple.asp",
    "Security Week":"http://feeds.feedburner.com/securityweek",
    "Computer World":"https://www.computerworld.com/index.rss",
    "US-CERT":"https://www.us-cert.gov/ncas/current-activity.xml",
    "Bleeping Computer":"https://www.bleepingcomputer.com/feed/",
    "Naked Security":"https://nakedsecurity.sophos.com/feed/",
    "CVE Details":"https://www.cvedetails.com/vulnerability-feed.php?vendor_id=0&product_id=0&version_id=0&orderby=2&cvssscoremin=0",
    "News 24":"http://feeds.news24.com/articles/fin24/tech/rss",
    "Reuters Company":"http://feeds.reuters.com/reuters/companyNews",
    "Reuters Tech":"http://feeds.reuters.com/reuters/technologyNews",
    "TechCrunch":"http://feeds.feedburner.com/TechCrunch/",
    "TechMeme":"https://www.techmeme.com/search/query?q=rss",
    "ARS Technica":"http://feeds.arstechnica.com/arstechnica/index",
    "The Verge":"https://www.theverge.com/rss/index.xml"
    }

