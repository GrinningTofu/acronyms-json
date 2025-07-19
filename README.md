use the following AI prompt to format your acronyms, and add them to the json list in between the [] brackets

I will give you acronyms in plain text. Each one includes:
- The acronym (with or without spaces)
- A short description
- A list of its letters and what each stands for

Please format each one into this json structure:

{
  "acronymString": "ACRONYM OR MNEMONIC PHRASE",
  "description": "Short description of the acronym's purpose",
  "expansion": [
    { "letter": "A", "meaning": "Meaning for A" },
    { "letter": "B", "meaning": "Meaning for B" }
  ]
},

Important:
- If the acronym is a **real word or abbreviation** (e.g. "FIRMS", "API"), keep it **unspaced**
- If the acronym is a **mnemonic phrase** (e.g. "I LOVE MONEY"), preserve the **spaces**
- Each object must end with a **comma**, so it's ready to be pasted into a list
- Do **not** wrap the output in an array, and put a comma at the end of the last acronym object
- Output only raw json object literals, one per acronym
- Use the correct double apostrophe, "
