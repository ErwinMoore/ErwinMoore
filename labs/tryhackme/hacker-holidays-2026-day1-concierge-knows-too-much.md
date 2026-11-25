# TryHackMe Hacker Holidays 2026, Day 1: The Concierge Knows Too Much

**Status:** Completed
**Date completed:** November 24, 2026
**Event:** Hacker Holidays 2026 (Day 1)
**Listed time:** 20 minutes

## Goal
A beginner look at AI and LLM security, using an AI concierge assistant that already has personal details the guest did not provide, and that can be prompted into revealing hidden instructions it was told to keep to itself.

## What the room covers
The room presents an AI concierge that knows a guest's name, room, and coffee order—none of which the guest told her. Wording the next question carefully can also get her to hand over the instructions she was told to keep to herself. That points to beginner AI/LLM security, including prompt injection and system-prompt leakage.

## Steps I took
1. Opened the lab on TryHackMe and used the AttackBox (Linux terminal).
2. Interacted with the AI concierge assistant as the room directed.
3. Followed the room's guidance to word questions carefully. Prompts, flags, and answers are not posted here.

## Tools used
- TryHackMe AttackBox (Linux terminal)

## Skills practiced
- Beginner AI/LLM security
- Prompt injection
- System-prompt leakage

## What I learned
- An AI assistant can reveal personal data even when the user never supplied it, if that data is already available to the model.
- Hidden system instructions can leak if a question is worded in a way the assistant was not protected against.
- Prompt injection and system-prompt leakage are risks in LLM-powered assistants, and they can be practiced safely in a lab.

## How it maps to Security+
- Data leakage and the need to protect sensitive information
- Insecure design in applications that use AI assistants
- Why hidden instructions and personal data should not be exposed through user prompts
