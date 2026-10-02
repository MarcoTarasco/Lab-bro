<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo/labmate_logo_dark.png">
    <img src="logo/labmate_logo_light.png" alt="labmate — your bench companion" width="460">
  </picture>
</p>

**One HTML file. Your whole bench.** Inventory, custom databases, protocols, an
experiment notebook and a drawer full of molecular-biology calculators — no server,
no account, no sign-up. Everything lives in your own browser, on your own machine.

> Built for a zebrafish lab, useful in any wet lab.

## ⬇️ Get it

Download **`labmate.html`** from the [**Releases**](../../releases/latest) page,
then just double-click it. That's the whole installation.

It works offline, straight from your hard drive — Excel import/export included
(the spreadsheet engine is baked into the file).

**A few house rules**

- Your data is stored in that browser's local storage, so open LabMate from the
  **same file path in the same browser** each time, and it will be there.
- Nothing is ever uploaded anywhere. There is no cloud, and no one else can see it.
- Because it is browser storage, clearing your browsing data clears LabMate. Set a
  backup folder in Settings and hit **💾 Save Backup** regularly — it writes a full
  JSON (exact restore) plus a readable Excel workbook.

---

## 🧪 Inventory

Reagents, consumables and equipment in one list: quantities, lots, expiry,
location, supplier, hazard tags and SDS links. Low stock and expiring items are
flagged for you on the first screen.

![Stock overview](screenshots/01_dashboard.png)

Filter by category — here the example **chemicals** that ship with the app:

![Chemicals](screenshots/02_chemicals.png)

…and the **equipment**, tracked right next to the reagents:

![Equipment](screenshots/03_equipment.png)

Click any item — anywhere on its row — to read the whole record; hit Edit to change it:

![One item, every field](screenshots/04_item_record.png)

Everything below its minimum is collected into an **order list** you can export:

![Order list](screenshots/05_order_list.png)

…and everything about to expire (or already expired) has its own watch list:

![Expiry watch](screenshots/06_expiry_watch.png)

---

## 🗄️ Databases

Build your own tables — primers, plasmids, probes, fish lines, equipment logs —
with your own columns, batch editing, and Excel/CSV/JSON import & export.

An **equipment log** with models, serials, service dates and status:

![Equipment log](screenshots/07_equipment_log.png)

A **primer database**; anything with a sequence column also gets QC and
duplicate-finder tools:

![Primer database](screenshots/08_primers_database.png)

---

## 📖 Protocols

Write a protocol once, then run it from the screen.

![Protocol library](screenshots/09_protocols.png)

Each protocol becomes a **tickable checklist** with coloured day-dividers; the
progress is saved, so a three-day protocol survives going home in between. Print a
clean bench copy whenever you prefer paper.

![Protocol checklist](screenshots/10_protocol_checklist.png)

---

## 📓 Experiments

A light lab notebook. Each entry has a date, tags, a status and notes — and every
tag becomes a filter.

![Experiment list](screenshots/11_experiments.png)

Inside, an **Excel-like grid with sheet tabs**: paste straight from a spreadsheet,
resize columns, undo a bad paste, and keep your PCR setup on a second tab next to
the results. Import a pile of .xlsx files and each becomes its own experiment.

![Experiment grid](screenshots/12_experiment_grid.png)

---

## ⚗️ Calculators

Build a solution once and let LabMate scale it — percentages, dilutions from stock,
ratios, molarity + MW, fill-to-volume:

![Recipe calculator](screenshots/13_recipe_calculator.png)

Save your master mixes and scale them to any number of reactions, with a printable
pipetting scheme:

![Reaction mix](screenshots/14_reaction_mix.png)

Work out the exact microlitres of vector and insert for **In-Fusion** or
**NEBuilder HiFi** assemblies:

![Assembly calculator](screenshots/15_assembly_calculator.png)

Paste a sequence and add the fixed flanks for sgRNAs or in-situ probes:

![Oligo design](screenshots/16_oligo_design.png)

Plus C1V1, molarity, dilutions, oligo resuspension and ng↔pmol in the
**Lab Calculators** panel.

---

## 📊 Analytics & search

See where your stock sits and what it is made of:

![Analytics](screenshots/17_analytics.png)

And find anything, anywhere, with **Ctrl/⌘ + K** — items, database records,
protocols, recipes, experiments:

![Search everything](screenshots/18_search_everything.png)

---

## ⚙️ Settings

Ten themes, a per-colour customiser, your backup folder, and the trial panel:

![Settings](screenshots/19_settings.png)

---

## 🌱 What you get on first open

LabMate starts with example data so nothing is a blank page: ~36 example items
(chemicals, enzymes, kits, buffers, antibodies, consumables, equipment), example
primer / plasmid / probe / equipment-log databases, four example protocols, two
recipes and two example experiments.

They are only there to show what goes where — clear them in one click under
**Settings › Reset Data**, or simply edit them into your own work.

---

## ⏳ Trial & access codes

This build runs as a **90-day trial**, counted from the first time you open it. The
footer shows how many days are left.

When the time is up, the app is replaced by a lock screen: **nothing is deleted**,
your data stays in the browser, and you can still download a copy of it from that
screen. A valid access code starts a fresh 90 days.

![Trial lock screen](screenshots/20_trial_lock_screen.png)

**Want a code?** Write to **Marco Tarasco** —
[marco.tarasco@mpi-bn.mpg.de](mailto:marco.tarasco@mpi-bn.mpg.de)

---

<sub>LabMate v25 · single-file web app · © Marco Tarasco, Max Planck Institute for Heart and Lung Research</sub>
