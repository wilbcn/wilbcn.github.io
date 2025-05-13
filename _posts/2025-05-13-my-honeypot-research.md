---
layout: post
title: "My SSH Honeypot Research Blog"
date: 2025-05-13 17:40:00
categories: [Research, Honeypots]
tags: [Cowrie, SSH, deception, realism]
---

Welcome to my first blog post documenting my ongoing research into SSH honeypots!

Honeypots are cybersecurity tools designed to lure attackers away from legitimate systems and gather intelligence on their methods and motivations. In today’s threat landscape, where attackers are increasingly capable of identifying deceptive systems, effective honeypot realism is more critical than ever.

This project focuses on **SSH honeypots**, which remain a frequent target due to the widespread use and often weak security of SSH servers. Using **Cowrie**, a medium-interaction SSH honeypot framework, I am deploying two environments with varying levels of realism—one with enhanced shell-level deception, and another that also includes contextual services like a web server and database.

The goal is to explore whether increasing system realism leads to deeper, more complex attacker engagement. Stay tuned as I share findings and insights throughout the project!
