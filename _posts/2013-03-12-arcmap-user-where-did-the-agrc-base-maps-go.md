---
layout: post
status: publish
published: false
title: 'ArcMap User: "Where did the AGRC Base Maps Go?'
author:
  display_name: Bert Granberg
  login: Bert Granberg
  email: bgranberg@utah.gov
  url: ''
author_login: Bert Granberg
author_email: bgranberg@utah.gov
wordpress_id: 12878
wordpress_url: http://gis.utah.gov/?p=12878
date: '2013-03-12 18:03:34 -0600'
date_gmt: '2013-03-13 00:03:34 -0600'
categories:
- Uncategorized
- Featured
tags: []
---
<p>Just a quick note to let everyone know that the pre-rendered, super fast AGRC base map services got new names when they were ported to our new ArcGIS 10.1 server which went live March 1. 2013. Web applications were not impacted by this change, but ArcMap users will need to re-add the base maps to existing projects.</p>
<p>The information on adding the base maps services has been updated on the <a href="{{ "/data/sgid-base-map-services-arcmap/" | prepend: site.baseurl }}">base maps page</a>. </p>
<p>[Spoiler alert] The base maps are at the same server url (mapserv.utah.gov) but are now in their own folder called BaseMaps. AGS 10.1 did not allow for hypens in the base map names, so, since the name needed to change (breaking existing links), we thought it was time to give them their own folder. </p>
<p>If you noticed the electricity dimming in January, it might be because the base maps were being updated (lots of cpu power needed) prior to the server switch-over. They should reflect the most current data in the SGID as of late December, 2012.</p>
