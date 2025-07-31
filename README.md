# Helluva Boss: Fuck-O-Meter

### Overview:
I wrote a Python script (which I call the **"fuck-o-meter"**) that processes *Helluva Boss* episode transcripts across all available seasons (including the shorts) and tracks every way the word **"fuck"** is used in the show. It counts each variation (e.g. `"fuck"`, `"fucking"`, etc.) — which you can see on the first slide — and tallies how often each character says them, including total F-bomb count.

### Data Selection:
I decided to stick to the **main cast** and some of the **supporting cast** for this project. I also filtered out any characters who only said some variation of "fuck" *twice*. Every character shown here has said some variation of the word at least **three times**.

### Purpose:
I did this mostly out of **curiosity**. I've seen similar breakdown posts before, but I wanted to create my own version that's **up to date** with where the show's currently at. With a new short and episode on the way, it felt like the perfect time to dive in and see how things currently stack up.

### Specs:
Python was the backbone of the whole project. All of the main **data processing logic** was written from scratch, aside from using `pathlib` to read directories. I used `matplotlib.pyplot` to build the visualizations — i.e. the horizontal and vertical bar charts. I also used `matplotx` to give a **dark theme** to every chart you see here. I used a bit of **regex** (regular expressions) to help clean up the transcript lines and identify dialogue by character name tags. Regex also helped me track each character's **unique F-bomb variants** and tally their counts, including overall totals.

### Results + Reflection:
Unsurprisingly, **Blitzo** topped the leaderboard with the highest total F-bomb count by a huge margin. This is especially noticeable when you look at all the various ways he uses the word. Aside from that, it was still fun to see the numbers laid out visually. It was especially nice to **quantify** all the ways a character has dropped the F-bomb on this show.

On a couple of notes, I did notice that certain F-bomb variations didn't get properly formatted (e.g. `"myfuckingself"`), but hopefully that's not too distracting. I won't claim this is a **definitive** count. For all I know, my script could have missed a couple of steps — but I'm confident these capture **most** of the possible F-bomb cases.
