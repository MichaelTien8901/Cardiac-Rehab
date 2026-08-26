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

## Set 6 — Dance (aerobic) + dumbbells

* Source: [Exercise Set 6.pdf](Exercise%20Set%206.pdf)

| Routine | Standing | Seated |
| --- | --- | --- |
| Aerobic — dance | [?video](https://www.youtube.com/watch?v=8HN1DbBtTcA) | [video](https://www.youtube.com/watch?v=ogKlUrnZWUY) |
| Resistance — dumbbells | [video](https://www.youtube.com/watch?v=eKKMYX5fjW4) | [video](https://www.youtube.com/watch?v=E188slxISG8) |
| Cool down — seated yoga (optional) | — | [video](https://www.youtube.com/watch?v=3ZvmKOPoFVo) |
| *Jane Fonda:  Fat Burning Funk Dance Workout | [video](https://www.youtube.com/watch?v=uJLMS5bp0mI) | NA |

* No dumbbells? Water bottles or soup cans work.

* The PDF's printed dumbbell graphics cover goblet squat, bent-over close-grip
row, alternating chest press, unilateral shoulder press, elbow flexion (curl),
bent-over elbow extension (kickback), and a supported single-leg stance. All
are 1–3 sets of 10–15 reps with 60 seconds rest, except the balance hold —
2–3 sets of 15–30 seconds. The cool-down stretching graphics follow.

* This set also reprints the program's general strength-training guidance: never
hold your breath, learn the movement before adding weight, two seconds up and
three seconds down, and if you can't manage 8 reps the weight is too heavy.
Progress by adding 1–2 reps first; once you can do 15–17, add the smallest
weight increment available and drop back to 10–15.

## The 4-week resistance cycle

Resistance training rotates through four equipment types, one per week:

1. Bodyweight ← week 1
2. Dumbbells ← set 6
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

## Scaling the routine

The sets print the same advice for adjusting difficulty:

**Too easy** — repeat the routine once more; run it on consecutive days or with
no more than one rest day between sessions; combine two or three routines
back-to-back for a full hour; build volume by going more often (5 days/week) or
longer (30 minutes or more). Ask your Case Manager for harder options.

**Too hard** — do one activity a day (day 1 aerobic, day 2 resistance, day 3
walk), or split the routine across the day (morning aerobic, afternoon
resistance, evening stretch). Start with the seated options before the standing
ones, and keep moving through the day — any movement beats none. Ask your Case
Manager for easier options.

## Adding a new week

1. Drop the PDF in this folder as `Exercise Set N.pdf`, matching the number the
   program prints on the sheet — e.g. `Exercise Set 7.pdf`.
2. Add a section above with its video links, newest set last.

Extract the links with:

```bash
pdftotext "Exercise Set 7.pdf" - | grep -oE 'https?://[^ )>,]+' | sort -u
```
