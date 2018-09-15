---
layout: post
title: "Visual Studio Shortcut: Replace in Files"
categories: [Visual Studio, Shortcuts]
tags: [Visual Studio Shortcuts, Edit, Find and Replace]
---

Replace in Files: Ctrl + Shift + H

__Replace in Files__ is nearly the same as [Quick Replace], but it:
  * can include external files
  * captures the results in one of the Find Results windows
  
So how do we decide which to use? If I want to do a Replace Next in the current document, then I use [Quick Replace]. When I want to do a Replace All or act on more than the current document, then I use __Replace in Files__.

I wish pressing Enter in the __Replace in Files__ dialog would invoke Replace All, but instead it invokes Find Next. To invoke Replace All, use Alt + A.

![replace in files gif]({{"/assets/replace-in-files.gif" | absolute_url}})

[Quick Replace]: {{"/blog/visual-studio-shortcut-quick-replace"}}