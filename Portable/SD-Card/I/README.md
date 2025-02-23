
***

# Plans for an SD card edition

## SeansAudioDB

### SD Card edition I

| Specification | Condition |
|---|---|
| **Capacity** | `512 gigabytes or higher` |
| **File system** | `Btrfs` |
| **Manufacturer** | Either: `SanDisk` `Samsung` other/reliable |
| **Durabilitity:** | [See below](#Durability) |

#### Durability

Durability is not a goal. SD cards are one of the most fail-prone storage mediums. I have been given the advice that I should do frequent backups, instead of getting the `latest and greatest` SD card, as durability doesn't really matter here. This will also allow me to pay significantly less, and get more SD cards.

#### Clone factory

There should always be at least 3 SD cards ready with carbon-copies of all data. When an SD card fails, a new one should be purchased immediately, and immediately go to the "clone factory" and repeat.

#### Rate of backup

The latest 3 playlists will be backed up on a daily basis, as they are the only constant piece of new data at the moment. Backups will have to happen within 24 hours of any new/existing content being added/modified.

#### Benefits of Btrfs

1. Full Linux compatibility
2. All characters allowed (except for `/`)
3. Compression is baked in, a huge win for SD cards (since SD cards normally trade CPU cycles for file i/o due to how slow they are) 
4. File system is basically as durable as the SD card itself (abusive hotplugging (taking the SD card out while files are being copied/read, before unmounting) is not a complete loss, but it isn't recommended) system will rarely/never need to have the `fsck` command executed on it

***

### File info

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `1 (2022, Wednesday, August 24th at 7:51 pm PST)`

**Line count (including blank lines and compiler line):** `88`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

_Note that on 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

**You may need special rendering support for the `<details>` HTML tag being used in this document**

</details>

***

## File history

<details><summary><p lang="en"><b>Click/tap here to expand/collapse the file history section for this project</b></p></summary>

<details><summary><p lang="en"><b>Version 1 (2022, Tuesday, August 23rd at 7:51 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Started the file
- [x] Added the title section
- [x] Added the main table
- [x] Added the `Durability` section
- [x] Added the `Clone factory` section
- [x] Added the `Rate of backup` section
- [x] Added the `Benefits of Btrfs` section
- [x] Added the `file info` section
- [x] Added the `file history` section
- [ ] No other changes in version 1

</details>

</details>

***
