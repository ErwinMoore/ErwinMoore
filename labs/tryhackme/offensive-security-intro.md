# TryHackMe: Offensive Security Intro

**Status:** Completed
**Date completed:** November 21, 2026

## Goal
Get a first look at offensive security in a legal lab by attacking a fake bank website: find a hidden page and transfer money between accounts.

## Steps I took
1. Opened the fake bank site in a browser and reviewed the pages that were already visible.
2. Used a directory brute-force tool to look for hidden pages that were not linked from the main site.
3. Opened the hidden page and followed the lab guidance to transfer money between accounts.

## Tools used
- Web browser
- Directory brute-force tool

## What I learned
- Offensive security is about finding and using weaknesses the same way an attacker would, in a sanctioned lab.
- Pages can still be reachable even when they are not linked on the website.
- A site can look limited on the surface and still expose an unlinked page that can change an account.

## How it maps to Security+
- Reconnaissance and enumeration of a web application
- Why leftover or unlinked pages are a risk if they stay reachable
- Using an attacker mindset in a legal lab to understand what defenders need to protect
