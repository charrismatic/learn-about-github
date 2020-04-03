+++
weight = 20
+++

<h2 class="h1 mb-6">Chapter 2: Workflows</h2>


<div class="flex" style="display:flex; justify-content:center; align-items:center;">
<div>
{{< getimage src="github-logo.svg" class="plain" height="50" >}}
{{< getimage src="git-logo.svg" class="plain" height="50" >}}
</div>
<span style="flex:0; padding: 0 1em; font-style: italic;">vs.</span>
{{< getimage src="dropbox-logo.svg" class="plain" height="90" width="300" >}}
</div>

---

{{< getimage src="dropbox-logo.svg" class="plain" height="90" width="260" >}}

**Dropbox**: is a file hosting service

<section class="text-left lh-175">
{{< frag c="1. DB brings files together in one central place." >}}<br>
{{< frag c="2. By creating a special folder on the user's computer." >}}<br>
{{< frag c="3. All folders contents are sync'd to DB servers." >}}<br>
{{< frag c="4. DB servers keep all the users computers and devices sync'd." >}}<br>
{{< frag c="5. DB keeps the same files up-to-date on all devices." >}}<br>
</section>

---

{{< getimage src="dropbox-logo.svg" class="plain" height="90" width="260" >}}

**Dropbox**: is a file hosting service

- Dropbox is effortless, automatic, and require no thought
- These features also are what make it terrible for project work
- When any file is changed DB uploads changed pieces, whenever possible
- DB uses SSL for transfers and synchronization
- DB stores the data via Advanced Encryption Standard (AES)-256 encryption
- DB is constantly watching and rehashing every file in your account

---


{{< section >}}
<h2 class="h1">Dropbox: for project sync</h2>
{{< getimage src="git-vs-dropbox1.png" class="plain" >}}
{{< /section >}}

{{< section >}}
{{< getimage src="git-vs-dropbox2.png" class="plain" >}}
{{< /section >}}

{{< section >}}
{{< getimage src="git-vs-dropbox3.png" class="plain" >}}
<div class="fs-m4">ref: <a href="https://www.quora.com/Should-I-use-Dropbox-instead-of-Git-for-2-coders-In-terms-of-going-really-fast-and-working-on-things-at-the-same-time-Im-thinking-it-may-be-uber-productive-to-use-Dropbox-for-its-instant-syncing-instead-of-Git-Github-What-are-the-pros-cons" class="">quora.com</a></div>
{{< /section >}}

</blockquote>

----


{{< getimage src="git-logo.svg" class="plain" height="90" width="260" >}}

{{< getimage src="git-branching1.png" class="plain" >}}
- `git` is purposeful
- error correcting
- requires some thought
- merges all changes before updating

---

{{< section >}}
<h2 class="h1">Things you can't on DropBox</h2>
<h3 class="h2">Branching</h3>
{{< getimage src="git-data-model-2.png" class="plain" >}}
{{< /section >}}

{{< section >}}
<h3 class="h2">Contributions Stats</h3>
{{< getimage src="git-contributions.png" class="plain" >}}
{{< /section >}}

{{< section >}}
<h3 class="h2">Visualizations</h3>
{{< getimage src="git-vis.png" class="plain" width="100%">}}
{{< /section >}}
