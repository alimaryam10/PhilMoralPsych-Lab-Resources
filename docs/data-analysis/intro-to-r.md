---
layout: default
title: Intro to R
parent: data-analysis
nav_order: 1
---

# What is R and RStudio?

R is a free, open-source programming language purpose-built for statistical analysis. RStudio is an Integrated Development Environment (IDE) for R — essentially a wrapper that gives you a more user-friendly interface for coding. You should download both.

# Downloading R and RStudio

Visit [this page](https://rstudio-education.github.io/hopr/starting.html) for instructions on downloading both R and RStudio.

# Setting up a working directory

A working directory is the folder you set as the default location for any files you read into R or save out of R. Setting one up properly helps keep your data, scripts, and plots organised in one place. Follow the steps below to get set up.

## Step 1: Create a folder on your desktop

This folder will be your working directory. Give it an intuitive name (e.g., "Dissertation Analyses") so you can find it easily later.

## Step 2: Export your data from Qualtrics

1. Open your survey on Qualtrics.
2. In the top toolbar, click **Data & Analysis**.
3. Above your responses, on the right, click **Export & Import**.
4. Select **Export Data...** from the dropdown menu.
5. Make sure the data table type is set to **CSV** at the top of the box.
6. Click **Export values** to get your numeric dataset (i.e., the dataset where Likert variables appear as numbers).
7. Save this file in the folder you created in Step 1 and name it `num_data`.
8. Go back to Qualtrics and select **Export labels** to get your text dataset (i.e., the dataset where variables appear as text).
9. Save this file in the same folder and name it `text_data`.

## Step 3: Create an R Project

1. Open RStudio.
2. Click the second button in the top-left toolbar (a blue box logo with an "R" on it and a green plus sign in the corner).
3. Select **Existing Directory**.
4. Click **Browse** and select the folder you created in Step 1.

## Step 4: Create your code script

1. Click the first button in the top-left toolbar (a white page logo with a green plus sign in the corner).
2. Select **R Markdown...** from the dropdown menu. Many people code in a basic R Script, but we prefer R Markdown, since it lets you "chunk" your code and produce a nicely knitted HTML file with your results explained and summarised alongside the code.
3. Delete the default content on the page and edit the YAML header as needed (details below)

The YAML header sets the "settings" for your knitted document. See an example of how we've set things up in the past:

   <img width="213" height="168" alt="Screenshot 2026-07-09 at 14 58 50" src="https://github.com/user-attachments/assets/e437a16c-e8ca-4fea-b41d-fef9eeb3032e" />

   * `title: "My Dissertation"` — sets the title that appears at the top of your knitted document
   * `date: "`r Sys.Date()`"` — inserts today's date automatically by running the R command `Sys.Date()` inline, so you never have to update it manually
   * `output: html_document:` — tells R Markdown to knit your file into an HTML page (as opposed to a PDF or Word doc)
   * `toc: true` — adds a table of contents to the top of your knitted document, generated automatically from your headers (`#`, `##`, etc.)
   * `toc_depth: 2` — limits the table of contents to headers up to level 2 (i.e., `#` and `##`, but not `###` and beyond), keeping it from getting cluttered
   * `number_sections: true` — automatically numbers your headers (1, 1.1, 1.2, 2, etc.), which is handy for referencing specific sections later
   * `theme: readable` — sets the visual styling of the knitted page; "readable" is one of several built-in Bootstrap themes (others include `cerulean`, `journal`, `flatly`, etc.) that control fonts, colours, and spacing

# What is a knitted document, and why make one?

When you write an R Markdown file (`.Rmd`), you're combining two things in one document: your write-up (in plain text/Markdown) and your R code (in "chunks"). **Knitting** is the process of running that file through R — it executes all your code chunks, captures the output (tables, plots, statistics), and weaves it together with your text into a single, polished output file (HTML, PDF, or Word).

This is especially useful for:

* **Reproducibility** — your analysis and your results write-up live in the same file, so anyone (including future-you) can see exactly which code produced which result. No more copy-pasting numbers from the console into a Word doc and losing track of where they came from.
* **Clean presentation** — the final knitted document hides your messy code by default (unless you choose to show it) and presents a tidy, readable report with a table of contents, numbered sections, and formatted output.
* **Inline reporting** — you can embed R code directly into your sentences (e.g., "the mean age was `` `r mean(age)` ``"), so your reported statistics are always pulled live from your actual data rather than typed in manually and prone to error.
