# Cutout and Upscale in One Workflow: Where the Edges Fail

Background removal and upscaling interact: a matte made at low resolution has soft edges that upscaling turns into halos. Measured edge-width growth across both orders, plus why a higher-resolution matte cannot recover hair strands under two source pixels.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-remove-background-and-upscale/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
