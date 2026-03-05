# Future Interns: Task 2 - AI Content Marketing using UGC Ads

## Overview
This repository contains the deliverables for Task 2 of the Prompt Engineering Internship. The objective was to design a reusable prompt framework capable of generating authentic, high-converting User Generated Content (UGC) ad scripts for short-form video platforms.

## Product Profile 
* **Product:** FrostBite Mobile Gaming Cooler
* **Type:** D2C Tech Gadget
* **Target Audience:** Mobile gamers dealing with device overheating and performance throttling.

## Prompt Engineering Logic
The master prompt (`master_prompt.txt`) utilizes a structured variable system to define the product, audience, and platform context. By explicitly requesting the "Problem -> Solution -> CTA" framework and mandating an "authentic, raw" tone, the LLM is constrained from generating overly corporate, polished marketing speak. The prompt outputs a comprehensive Ad Pack, including multiple hook variations (Negative, Curiosity, Transformation) and multiple distinct ad scripts to test against audience fatigue.

## Included Files
1. `master_prompt.txt`: The system instruction set.
2. `ugc_ad_pack.txt`: The AI-generated UGC hooks, multiple scripts, and captions.

## Tools Used
* Generative AI (Google Gemini)
* GitHub for version control and documentation
