---
title: "Post mortem on Linear security incident on March 24th, 2026"
url: "https://linear.app/now/linear-incident-on-mar-24th-2026"
date: "2026-04-06"
author: ""
feed_url: "https://linear.app/rss/now.xml"
---
On Tuesday March 24, a code change we deployed caused data from private teams to be accessible to other members within the same workspace. During a window of approximately one hour, 12:07am through 1:10am UTC, workspace members, including guest users, may have had access to data outside their normal team permissions. The issue was identified, code change reverted, and affected client sessions cleared within hours of detection. We notified the owners/admins of affected workspaces by email on Thur
