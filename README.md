## Categorisation Helper
This is a small tool to help categorise a list of people or programs into the 5 areas of the Shift m2M program. 

## CSV Format
**Required headers:** `ID, Firstname, Lastname` (exact casing not enforced; they are matched case‑insensitively).

**Optional header:** `Category`.

Multiple categories (Programs mode only) are separated by semicolons (`;`). Example:

```
ID,Firstname,Lastname,Category
102,Sam,Lee,Win
103,Ava,Ng,
P1,Alpha,,Connect; Build; Train
```

### Notes
- Leave `Category` blank if uncategorised.
- Do not use commas inside the Category field; only semicolons.
- Recognised categories: Connect, Win, Build, Train, Send/Multiply.
- When uploading a list of programs (Multiple mode), put the program name in `Firstname` and leave `Lastname` blank.

## Disclaimer
This tool is not affiliated with "Shift m2M", "Power to Change", or any ministry. It is experimental and provided "as is" without warranty. Data is stored only in your local browser (localStorage); clearing your cache or using another device will remove it. Do not enter sensitive or personal information beyond basic IDs and names—you are responsible for privacy compliance. Categorisation labels are subjective aids, not assessments.