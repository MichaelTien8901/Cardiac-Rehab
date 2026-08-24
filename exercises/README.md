# Exercise Sets

Weekly exercise sets from the VGH Virtual Cardiac Rehab program, plus clickable
copies of the video links buried inside them.

> **Why this file exists:** GitHub's inline PDF viewer rasterizes each page, so
> the links printed in the PDFs are not clickable on the GitHub website. The
> tables below mirror those links in Markdown so they work from any browser or
> phone. To use the PDFs with working links instead, hit "Download raw file" on
> the PDF's page and open it in a normal PDF reader.

## Week 1 — Introduction (bodyweight)

Source: [First Week Exercise Set (Introduction).pdf](First%20Week%20Exercise%20Set%20(Introduction).pdf)

| Routine | Standing | Seated |
| --- | --- | --- |
| Aerobic | [video](https://www.youtube.com/watch?v=u08lo0bESJc) | [video](https://www.youtube.com/watch?v=ypk6FwMxHnI) |
| Resistance — bodyweight | [video](https://www.youtube.com/watch?v=yjyjr9RCdOk&list=PLkETa5i0ewgX6_Dfb5XeraB2bfzornvp5&index=10) | [video](https://www.youtube.com/watch?v=mndeL_NnU7E) |

Warm up and cool down are not videos — 5 minutes of light activity to start, and
the printed stretching graphics in the PDF to finish. Hold each stretch 20–30
seconds, pain-free, and repeat 2–3 times.

The standing resistance video is item 10 of YouTube playlist
[`PLkETa5i0ewgX6_Dfb5XeraB2bfzornvp5`](https://www.youtube.com/playlist?list=PLkETa5i0ewgX6_Dfb5XeraB2bfzornvp5),
which is where the other routines in the cycle are likely to be found.

## The 4-week resistance cycle

Resistance training rotates through four equipment types, one per week:

1. Bodyweight ← week 1
2. Dumbbells
3. Bands
4. Balance / posture

No equipment on hand? Omit it and follow the movements through, or stay with
equipment you already have and reuse the earlier video.

## Session structure

Every session, regardless of week:

| Part | Frequency | Notes |
| --- | --- | --- |
| Warm up | every session | ~5 min light activity. Do not skip. |
| Aerobic | up to 5 days/week | Start at 2–3 days if new to exercise. |
| Resistance | 2–3 days/week | At least 1 rest day in between. |
| Cool down | every session, stretches daily | Do not skip. |

Aerobic and resistance can be done on separate days and combined later as you
progress. Your Case Manager sets the frequency that's right for you — the
numbers above are the program's general guidance, not a prescription.

## Adding a new week

1. Drop the PDF in this folder as `Week NN Exercise Set (Focus).pdf` — e.g.
   `Week 02 Exercise Set (Dumbbells).pdf` — so it sorts in program order.
2. Add a section above with its video links, newest week last.

Extract the links with:

```bash
pdftotext "Week 02 Exercise Set (Dumbbells).pdf" - | grep -oE 'https?://[^ )>,]+' | sort -u
```
