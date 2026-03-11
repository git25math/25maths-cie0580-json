# 25maths-cie0580-json

CIE 0580 Mathematics structured data — **Single Source of Truth**.

## Files

| File | Description |
|------|-------------|
| `papers-cie.json` | All 4,107 questions with Block[] structure |
| `syllabus-cie.json` | CIE 0580 syllabus (9 chapters, 72 sections) |
| `knowledge-cie.json` | Knowledge points per section |

## Data Model

```json
{
  "id": "0580-2025OctNov-Paper43-Q01",
  "stem": [{ "type": "text", "content": "..." }],
  "parts": [{ "label": "(a)", "content": [...], "answer": {...}, "marks": 1 }],
  "_rawBody": "\\begin{parts}\\n..."
}
```

## Usage

ExamHub fetches this data for web rendering.
Export scripts reconstruct LaTeX from this data.
