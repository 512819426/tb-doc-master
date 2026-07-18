# Word and PDF Handling Guide

## General rule

Use structured extraction where possible. Preserve tables, headings, numbering, and clause references because bid requirements often live inside forms and appendices.

## Word files

For `.docx`:

- Extract paragraphs and tables.
- Preserve heading order.
- Keep table row/column meaning.
- Inspect required forms and fixed templates.
- If modifying an existing proposal, preserve formatting where feasible and avoid rewriting unrelated content.

For legacy `.doc`:

- Convert or ask the user for `.docx` if the environment cannot read it reliably.
- If conversion is needed, state the limitation.

## PDF files

For text PDFs:

- Extract text page by page.
- Preserve page numbers for traceability.
- Pay special attention to tables, scoring methods, forms, and appendices.

For scanned PDFs:

- State that OCR is required.
- After OCR, warn that key clauses, numbers, dates, and tables require manual confirmation.
- Do not rely on low-confidence OCR for bid bond, deadline, price ceiling, qualification, or disqualification clauses without warning.

## Table extraction

Tables are critical. Treat these table types as high priority:

- Scoring method
- Eligibility review
- Compliance review
- Technical parameter table
- Commercial terms
- Price table
- Required document list
- Deviation table
- Contract annex

If a table cannot be extracted cleanly, summarize the issue and request a clearer source or manual confirmation.

## Traceability

When possible, include source location:

- File name
- Page number
- Section title
- Clause number
- Table name

Traceability is especially important for risks, scoring responses, and deviation tables.
