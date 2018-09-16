---
layout: post
title: "Visual Studio Shortcut: Go To Implementation"
categories: [Visual Studio, Shortcuts]
tags: [Visual Studio Shortcuts, Edit]
---

Go To Implementation: Ctrl + F12

In the previous post we learned about [Go To Definition] and how invoking it on an abstract/interface symbol will navigate to the abstract/interface definition. But what if we actually want to see an implementation? That's where __Go To Implementation__ comes in.

If there is only one implementation, then navigation will take you directly to it. If there is more than one, then the implementations will be listed in an "Implementations" window. You can then select the desired one using the mouse, up/down arrows, or the [Go To Next/Previous Location] shortcuts.

![go to implementation gif]({{"/assets/go-to-implementation.gif" | absolute_url}})

[Go To Definition]: {{"/blog/visual-studio-shortcut-go-to-definition"}}
[Go To Next/Previous Location]: {{"/blog/visual-studio-shortcut-go-to-next-location"}}