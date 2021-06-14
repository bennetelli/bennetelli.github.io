---
layout:     post
title:      "Failure is not an option"
subtitle:   "Many say exploration is part of our destiny, but it’s actually our duty to future generations."
date:       2014-07-08 12:00:00
author:     "Start Bootstrap"
header-img: "img/post-bg-03.jpg"
---

aws-java-sdk-bom vs direct dependency

Although I am a Maven user since many years, I recently came across bill of material dependencies. 
That concept was quite new to me and I've never used it before so I decided to write a blog post about it. 
Maybe this concept new to someone else as well.

<h1>What is a Bill of Material dependency?</h1>
BOM is one of the few ways Spring helps us forget about issues related to transitive dependencies and focus solely on our project requirements.

So when we generally create a large scale project with dozens or hundreds of dependencies, chances are multiple of them use something common internally by transitive dependencies. So, let's say we have a dependency called “common-3.0.0.RELEASE,” which is used by our logging artifact and “common-2.9.0.Release” used by our testing framework. In such a case, we have a conflict. We need to ensure we get a working version so that both the artifacts can work together in synergy.

<h1></h1>
