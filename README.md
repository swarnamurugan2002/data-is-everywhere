# Data Is Everywhere: Finding the Story in the Numbers

An interactive lesson on collecting, cleaning, analyzing and visualizing data, built around one real-world question: **why is the school Wi-Fi slow?**

Prepared by **Dr. Swarna Sethu**, Assistant Professor, Computer Information Science, Technology Department, Missouri Southern State University, for the Bentonville Schools Tech Club (Mission 1: Data).

**Open the lesson board:** `https://<your-username>.github.io/data-is-everywhere/`

## What's inside

| File | What it is |
| --- | --- |
| `index.html` | The click-through lesson board, shown during the session |
| `handout/Data-Is-Everywhere-Handout.docx` | The printable student handout |
| `data/wifi_tests.csv` | The sample dataset used in the lesson: 60 speed tests |

## The lesson

Every data job follows the same five stages. The board walks through each one with the Wi-Fi case, using free no-code tools.

| Stage | The question it answers | Tools used |
| --- | --- | --- |
| 1. Collect | What evidence do we need? | Google Forms, Speedtest app |
| 2. Clean & store | Can we trust every row? | Google Sheets |
| 3. Analyze | What pattern is in the data? | Sheets pivot tables, AI assistants |
| 4. Visualize | How do we show it so anyone sees it? | Sheets charts, Looker Studio, Canva |
| 5. Decide | So what should happen? | The insight formula |

## Using the board

- **Enter**, **→** or a presentation clicker: next step
- **←**: back one step
- At the end of a trace, the next press opens the next board.
- The sections list on the left jumps to any board.

## Try the sample data

1. In Google Sheets, choose **File → Import → Upload** and select `data/wifi_tests.csv`.
2. Choose **Insert → Pivot table**.
3. Set **Rows** to `location`, **Columns** to `time`, and **Values** to `speed_mbps`, summarized by **AVERAGE**.

The cafeteria at noon averages 22 Mbps. Every other place and time is 68 or higher.

> The Wi-Fi data is **made up for teaching**. It is realistic, but it was not measured at any real school.

## Credits

The lesson's real-world example is [BigBangData/Speedtest](https://github.com/BigBangData/Speedtest), a home Wi-Fi investigation published on GitHub. The board and handout show one small data file from that project, with credit; all rights to it remain with its author.
