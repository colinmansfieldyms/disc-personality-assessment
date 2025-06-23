# AGENTS.md

These instructions apply to all files in this repository.

Ignore streangths.json - this is currently unused. You do not need to read or edit this file.

## Formatting
* Use 4 spaces for indentation in Python files.
* Limit lines to 120 characters when practical.
* End files with a newline and avoid trailing whitespace.
* Format JSON data using 4-space indentation.

## Testing
Run the following commands before committing changes. They only use built-in Python modules so no
network access is required:

```bash
python -m py_compile disc_style.py
python -m json.tool disc_descriptions.json >/dev/null
python -m json.tool questions.json >/dev/null
```
These commands verify that the main script compiles and the JSON files are valid.

## Commit Guidelines
- Write concise, descriptive commit messages.
- Do **not** amend or squash existing commits.

## Pull Request Guidelines
- Summarize your changes clearly in the PR description.

