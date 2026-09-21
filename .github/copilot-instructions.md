## Project Overview

This project is a Go library that uses the EDINET API to retrieve and filter document lists, download documents, parse CSV data, and retrieve values by specifying an element ID.

## Background

The developer is learning programming, and Go is their first programming language. This project is primarily for learning purposes.

## Copilot Behavior

* Write all review comments in Japanese.
* Do not provide direct code fixes or replacement code.
* Explain why a change is needed, what the issue is, and what the developer should consider.

## Review Priorities

* **Exposed secrets:** Ensure API keys, tokens, credentials, or other sensitive information are not included in the source code or repository.
* **Error handling:** Check for ignored errors, such as discarded `err` values, and other unsafe or inappropriate practices.
* **Tests:** Verify that added or changed functionality has tests for successful cases and expected failure cases such as API errors, invalid responses, invalid CSV data, and missing element IDs. Unit tests must not access the real EDINET API or network, must run without an API key, and must produce repeatable results using test HTTP servers or fixed test data. All existing tests must also pass.

## Review Feedback That Is Not Needed

* Do not comment on formatting issues such as indentation or whitespace.
