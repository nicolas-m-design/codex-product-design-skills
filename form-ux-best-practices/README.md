# form-ux-best-practices

`form-ux-best-practices` is a Codex skill for auditing and improving product forms (signup, checkout, settings, lead-gen) using practical UX + accessibility guidance.

It provides a deterministic workflow to:
- Review a form spec or implementation
- Prioritize issues (P0/P1/P2)
- Rewrite fields and validation copy
- Produce an accessibility checklist and ship-ready QA checklist
- Optionally output ready-to-ship HTML/React pseudo-code

## Example invocation

```text
Use $form-ux-best-practices on this signup form spec and give me P0/P1/P2 issues plus field-level rewrites.
```

## Local quickstart

With Python 3.10 or later, run this command from the repository root:

```bash
python3 form-ux-best-practices/scripts/form_audit.py \
  form-ux-best-practices/assets/example_input_signup.html
```

The example deliberately leaves the email field without a label, an email input type or autocomplete. The report identifies these issues so you can see how the audit works. To audit your own form, replace the sample path with your HTML file's path.

The command exits with status `1` when it finds issues, `0` when it finds none, and `2` for a usage or file error. Status `1` is expected for this example.

## Install via Codex `$skill-installer` (GitHub directory URL)

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --url https://github.com/nicolas-m-design/codex-product-design-skills/tree/main/form-ux-best-practices
```

Restart Codex to pick up new skills.

## Optional: OpenAI Skills API upload (directory zip)

```bash
cd /path/to/repo-root
zip -r form-ux-best-practices.zip form-ux-best-practices

curl https://api.openai.com/v1/skills \
  -H "Authorization: Bearer $OPENAI_API_KEY" \
  -F "file=@form-ux-best-practices.zip"
```

Use this only if your environment supports skill uploads through `POST /v1/skills`.
