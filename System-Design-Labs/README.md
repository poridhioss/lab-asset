## System Design Lab asset

Public asset repository for **System Design Labs**. Images and diagrams live
here and are served over HTTPS via `raw.githubusercontent.com`, so they can be
embedded directly in the lab write-ups.

### Structure

```
system-design-labs
|-Milestones
|  |-MileStone-01
|  |  |-Module-01
|  |  |-Module-02
|  |  ...
```

- [**Milestones Overview**](./Milestones/README.md) — all 7 milestones and their modules

### Usage

Reference an asset by its raw URL:

```
https://raw.githubusercontent.com/poridhioss/lab-asset/main/system-design-labs/Milestones/<milestone>/<module>/<file>
```

Example:

```
https://raw.githubusercontent.com/poridhioss/lab-asset/main/system-design-labs/Milestones/MileStone-03/Module-11a/kv-store-architecture.png
```

> Keep filenames lowercase and hyphenated so raw URLs stay predictable.
