+++
title = "Git vs GitHub"
weight = 10
outputs = ["Reveal"]
layout = "bundle"
[reveal_hugo]
theme = "night"
margin = 0.2
+++


Chapter 1: Git vs GitHub

<div class="flex" style="display:flex; justify-content:center; align-items:center;">
{{< getimage src="git-logo.svg" class="plain" height="100" >}}
<span style="padding: 0 1em; font-style: italic;">vs.</span>
{{< getimage src="github-logo.svg" class="plain" height="90" >}}
</div>

---

- `git` is not GitHub.com
- GitHub.com uses `git` but it does way more

---
What most people think when they hear "GitHub"

{{% flex %}}
{{< getimage src="git-managed-team-flow.png" class="plain" >}}

```c
$ cat 0001-add-limit-to-log-function.patch
From 330090432754092d704da8e76ca5c05c198e71a8 Mon Sep 17 00:00:00 2001
From: Jessica Smith <jessica@example.com>
Date: Sun, 6 Apr 2008 10:17:23 -0700
Subject: [PATCH 1/2] Add limit to log function

Limit log functionality to the first 20

lib/simplegit.rb |    2 +-
1 files changed, 1 insertions(+), 1 deletions(-)

diff --git a/lib/simplegit.rb b/lib/simplegit.rb
index 76f47bc..f9815f1 100644

--- a/lib/simplegit.rb  
+++ b/lib/simplegit.rb  
@@ -14,7 +14,7 @@ class SimpleGit  
end  

def log(treeish = 'master')  
-    command("git log #{treeish}")  
+    command("git log -n 20 #{treeish}")  
end  
```

{{% /flex %}}

---
Projects on GitHub _use_ git, but the platform is much more than file hosting for your project.

- Issue tracking
- Feature requests
- Task management
- Wikis
- Free web hosting
- Automated actions/triggers
- API for 3rd party apps and integration

---

As of January 2020, GitHub reports having over

- {{< span class="cl-red" >}}40 million{{< /span >}}users
- over {{< span class="cl-blue" >}}100 million{{< /span >}} repositories
- including at least {{< span class="cl-green" >}}28 million{{< /span >}} public

Making it the largest host of open-source code in the world.

---

{{< section >}}
<h2 class="h1">GitHub Feature Overview</h2>
{{< getimage src="github.com-explore.png" class="plain block" >}}
{{< /section >}}

{{< section >}}
<h2 class="h1">GitHub Feature Overview</h2>
{{< getimage src="github.com-marketplace.png" class="plain block" >}}
{{< /section >}}

{{< section >}}
<h2 class="h1">GitHub Feature Overview</h2>
{{< getimage src="github.com-project-board.png" class="plain block" >}}
{{< /section >}}

---

**GitHub is a huge community and very active**

<div class="fs-0 text-left">
<blockquote class="fs-m2 w-90p">
<p class="my-0">In the midst of the uncertainty and seriousness of COVID-19, we've been inspired to see a global community of scientists, government officials, journalists, programmers, and concerned citizens come together to collaborate on a variety of projects with the shared goal of understanding COVID-19 and coordinating on the best response.</p>
<p>Even though many of these projects aren't traditional software projects, the same collaborative development model is being applied to curated data sets, DIY instruction sets, and more.</p>
<div class="text-right">(March 23, 2020)<br>- GitHub Blog</div>
<div class="text-right"><a href="https://github.blog/2020-03-23-open-collaboration-on-covid-19/" class="fs-m4">github.blog/2020-03-23-open-collaboration-on-covid-19</a></div>
</blockquote>
</div>

---

{{< section >}}
<h2 class="h1">Project Highlight: <br>Covid19 India Tracker</h2>
<ul>
<li>New group</li>
<li>Created within the last 30 days</li>
<li>1,200 Stars</li>
<li>739 Forks</li>
<li>83 Open Issues</li>
</ul>
{{< /section >}}

{{< section >}}
<h2 class="h1">Covid19 India Tracker</h2>
{{< getimage src="github.com-covid19india.png" class="plain block" >}}
{{< /section >}}

{{< section >}}
<h2 class="h1">Covid19 India Tracker</h2>
{{< getimage src="covid19india.org.png" class="plain block" >}}
{{< /section >}}

{{< section >}}
<h2 class="h1">Covid19 India Tracker</h2>
{{< getimage src="github.com-covid19india-issues.png" class="plain block" >}}
{{< /section >}}

{{< section >}}
<h2 class="h1">Covid19 India Issue 13</h2>
{{< getimage src="github.com-covid19india-issues-13.png" class="block m-auto plain w-80p" >}}
{{< /section >}}
