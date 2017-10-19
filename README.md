## HCDS 513 Assingment A1
### Michael Grant
License: MIT

This project's goal was to scrape the wikimedia API and plot the mobile, desktop and total page counts and page views. This was done for the years spanning 2008/01/01 - 2017/09/30, when available, from the [English Wikipedia](https://en.wikipedia.org) site. 

The data was segregated into two types, pagecounts and pageviews. The former lists all views of the site including web crawlers or spiders. These are programs that are written to visit pages and usually scrape, or extract, needed information automatically. The latter contains views only by a human. 

In order to replicate this plot, make sure that all needed packages are installed (they are listed in the notebook) and then simply run the notebook as is. Enjoy!

---

The final data cotains has the folowing schema and a description of each variable follows.
 * year: the four digit year the data was collected
 * month: the two digit month the data was collected
 * pagecount_all_views: the total views for both humans and spiders/crawlers alike
 * pagecount_desktop_views: the desktop views for both humans and spiders/crawlers alike
 * pagecount_mobile_views: the mobile views for both humans and spiders/crawlers alike
 * pageview_all_views: the total views for only humans
 * pageview_desktop_views: the deskptop views for only humans
 * pageview_mobile_views: the mobile views for only humans

---

Source:

[Wikimedia Foundation](https://wikimediafoundation.org/wiki/Terms_of_Use/en "Terms of Use")

[Wikimedia API Docs for PageViews](https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end "Does not include spiders/crawlers")

[Wikimedia API Docs for PageCounts](https://wikimedia.org/api/rest_v1/#!/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end "Includes spiders/crawlers")
