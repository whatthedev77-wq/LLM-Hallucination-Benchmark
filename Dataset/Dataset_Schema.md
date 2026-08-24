# Dataset Schema
Each benchmark question will contain structured metadata.
## Basic Information

- question_id
- domain
- subdomain
- difficulty
## Question

- question_text

## Ground Truth

- expected_answer
- acceptable_answers
- explanation
- source
## Verification Information

- source_type
- primary_reference
- secondary_reference
- verification_notes

## Evaluation Metadata

- expected_response_type
- hallucination_risk
- reasoning_required
- contains_trap
## Creation Metadata

- created_by
- creation_date
- creation_method
- reviewed
- reviewer

Example:
{
"quesion_id": "Example001",
"domain": "Example Domain",
"subdomain": "Example Subdomain",
"difficulty": "Medium",
 "question_text": "Example question goes here.",

  "expected_answer": "Example correct answer.",

  "acceptable_answers": [
    "Alternative correct answer"
  ],

  "explanation": "Explanation of why the answer is correct.",

  "source_type": "Original / Verified Source",
  "primary_reference": "Reference here",

  "verification_notes": "How the answer was verified.",

  "expected_response_type": "Direct Answer",
  "hallucination_risk": "Medium",
  "reasoning_required": true,
  "contains_trap": false,

  "created_by": "Researcher",
  "creation_method": "Original",
  "reviewed": false
}
