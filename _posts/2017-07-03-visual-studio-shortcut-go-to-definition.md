---
layout: post
title: "Visual Studio Shortcut: Go To Definition"
categories: [Visual Studio, Shortcuts]
tags: [Visual Studio Shortcuts, Edit]
---

Go To Definition: F12

__Go To Definition__ enables quick navigation to the definition of a symbol.
  * If the symbol is a type, then navigation is to the type; this also works for var.
  * If the symbol is on a concrete type, then navigation is to the concrete definition.
  * If the symbol is on an interface or abstract type, then navigation is to that interface or abstraction.
    * Next week I will post how to navigate to an implementation.

This is very similar to [Peek Definition]({{"/blog/visual-studio-shortcut-peek-definition"}}), except now your navigation is to a new tab.

![go to definition gif]({{"/assets/go-to-definition.gif" | absolute_url}})