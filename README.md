# ObsidianSyncProject
Python Obsidian-iOS/Windows Sync Project
Switching from Notion - Obsidian, there seems to be methods for JS and Deno with serverless to deploy syncs, but there doesn't seem to be much that exists for Python. This Project will explore potential ways to get Obsidian to sync to iOS

If you're looking to just get something going, then you can use the JS version that's been fleshed out by thousands of contributers, i'll be using it as a resource while building this project.
https://github.com/vrtmrz/obsidian-livesync/tree/main

WHY?
I enjoy geeking out, I love Notion, It's helped me organize so many things in my life, but I found that overtime it seems to be fairly bloated in featuresets for what my purposes are, which is basically rapid note taking for my brain dumps. I want something that's quick, syncs, and is offline so that I never have to worry about databases being vulnerable, aka LastPass, I also don't have to worry about the longevity of Notion and the Security of my Data because it'll all be handled by me.

This is also a good chance for me to do an E2E Deployment using Python, I'm not sure if it's feasible yet, but let's find out!


Initial SCOPE:
- Must use Python
  - IDE: VSCode
- Must support syncing between iOS & Windows
- Serverless solutions with integrated functions to avoid hardware costs
  -Cloudflare R2?
  -IBM Cloudfront?
  -AWS S3 solutions?
  -Azure Blob?
  -Google Cloud?
- Must support all Obsidian Filetypes
- Don't comment on Code, instead make the Code inherently readable by using good filenames and having a standard.
        Use descriptive, specific names
        Use consistent casing - like_this (for python)
        Use full words
        Make names pronounceable
        Encode meaning
-CRON jobs Needed?

Potential ROADBLOCKS:
-Expensive
