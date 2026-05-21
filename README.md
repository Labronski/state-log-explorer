# State Log Explorer

A tool for parsing and visualizing raw application state logs. Transforms large, unstructured JSON logs into a clean, structured, human-readable format — making it practical to diagnose complex issues that would otherwise require manually reading thousands of lines of raw JSON.

---

## The Problem

When users report complex wallet or transaction issues, they can provide application state logs that contain the full snapshot of what was happening at the time of the problem. These logs are comprehensive but essentially unreadable in their raw form — deeply nested JSON objects with hundreds of keys, no clear hierarchy, and no signal about what's relevant.

Reading them manually is slow, error-prone, and requires knowing exactly what to look for. State Log Explorer ingests the raw log and surfaces the data that actually matters for the investigation.

---

## Features

- Paste or upload a raw JSON state log directly in the browser
- Parses and restructures the log into clearly labeled sections
- Surfaces key data points: wallet state, network configuration, transaction history, pending operations, and user activity
- Highlights anomalies and fields commonly associated with known issue patterns
- Removes noise — hides redundant, empty, or irrelevant fields by default
- Significantly reduces time spent on complex multi-factor investigations

---

## Use Cases

- Diagnosing stuck or missing transactions
- Identifying network misconfiguration issues
- Investigating wallet state corruption
- Reproducing and documenting bugs with full state context

---

## Stack

- **JavaScript** — log parsing and transformation logic
- **HTML / CSS** — frontend interface

---

## Notes

This is an internal tool and the live environment is not publicly accessible. Source code is not included as it contains environment-specific configurations. This README documents the project's purpose, design, and impact.
