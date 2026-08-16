---
title: "Making jsDelivr’s Origin More Reliable at Scale"
url: "https://www.jsdelivr.com/blog/making-jsdelivrs-origin-more-reliable-at-scale/"
date: "2026-08-10"
author: "Martin Kolárik"
feed_url: "https://www.jsdelivr.com/blog/rss"
---
When the original storage index was designed, jsDelivr tracked roughly 350,000 unique files. By the time we replaced it, that number had grown to more than 600 million. We moved the index from Redis to MariaDB, migrated storage from Amazon S3 to Wasabi, compressed and cleaned up the stored
