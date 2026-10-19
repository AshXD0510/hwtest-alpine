# hwtest-alpine

Live hardware test toolkit for x86-64 PCs and laptops, run from Alpine Linux.

## Planned tests

- **CPU:** full-load stress with temperature limit
- **Memory:** memtester with configurable passes
- **Battery:** charge, status, and health (skipped automatically on desktops)
- **Keyboard:** key input check (detected automatically)
- **Storage:** read-only SMART health summary with life remaining where reported, full report saved to file, and a 1 GB read test on internal disks

Results are shown on screen and saved to text files. Boot and removable disks are excluded. Write tests are not included in this version.

## Status

Planning. Scripts not yet written.
