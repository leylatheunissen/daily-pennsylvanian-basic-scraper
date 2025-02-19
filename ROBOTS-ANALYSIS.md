# Robots Analysis for the Daily Pennsylvanian

The Daily Pennsylvanian's `robots.txt` file is available at
[https://www.thedp.com/robots.txt](https://www.thedp.com/robots.txt).

## Contents of the `robots.txt` file on February 19, 2025.

```
User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /
```

## Explanation

Based on the contents of the robots.txt file, I am allowed to scrape the Daily Pennsylvanian's
website, but I must respect a 10 second delay between requests.

To break it down:
The user-agent * means the rule applies to all web crawlers and bots. 
Crawl-delay: 10 means that crawlers must wait 10 seconds between requests. 
Allow / means that all pages of the sites are accessible. 
