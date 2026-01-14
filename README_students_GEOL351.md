# GEOL351 Student Workspace (Spring 2026)

This repository is your **personal workspace for GEOL351**.  
You will keep it for the entire semester.

You will:
- view lab instructions (HTML) and lab notebooks (jupyter or quarto)
- keep notes or notebooks from labs
- develop your final project

You will **not** submit work through GitHub unless explicitly asked.

---

## What this repository is for

This repo has three main folders:

```
lab_site/            # lab instructions (pulled from the instructor)
work/            # your lab notes, notebooks, figures, scratch work
final_project/   # your final project materials
```

### Important rule
**Do not edit anything inside `lab_site/`.**

Labs are distributed from Github Classroom and updated centrally.  
If you need to modify something, copy it into `work/lab...`.

---

## How you get the labs

Lab instructions live in a separate instructor repository.  
You will **pull updates** from that repository as the semester progresses.

You only need to set this up once.

---

## One-time setup (GitHub Desktop)

1. Open **GitHub Desktop**
2. Clone *this* repository to your computer
3. In GitHub Desktop:
   - `Repository → Repository settings → Remotes`
   - Click **Add**
   - Name: `upstream`
   - URL:
     ```
     https://github.com/USC-GEOL351/geol351-labs-2026
     ```

That’s it. You are now connected to the lab materials.

---

## Weekly workflow

Each time a new lab is released:

1. Open GitHub Desktop
2. Click **Fetch origin**
3. Go to **Branch → Merge into current branch**
4. Select `upstream/main`
5. Click **Merge**

The new lab will appear in the `labs/` folder.

Open labs by right clicking the HTML file of interest and seclecting "open in browser" (or similar depending on your operating system).

---

## Where your work goes

- Notes, answers, notebooks → `work/`
- Final project → `final_project/`

You can organize these however you like.

---

## What you need to give the instructor

Nothing special.

By accepting the GitHub Classroom invite:
- your repository was created
- the instructor automatically has access

If asked to share work, make sure it is **pushed to GitHub**. Pushing to your repo will not push to the master class materials. 

---

## If something goes wrong

- If a merge fails: stop and ask for help
- If you edited something in `labs/`: revert it or re-pull
- If GitHub Desktop is confusing: ask early

You are **not** expected to be Git experts. Frankly, I'm not an expert either, but if you have trouble we'll figure it out, or come up with an alternative workflow.
