# HTML Injection – Screenshot Analysis

This screenshot demonstrates a basic **HTML Injection vulnerability**, where user input is rendered directly into the page without proper sanitization.

## Screenshot

![HTML Injection Example](screenshots/html-injection-example.png)

## What is happening

- User-controlled input is injected directly into the HTML output
- A malicious `<a>` tag was inserted
- This allows redirection to external websites

## Why this matters

HTML Injection can be used as a first step toward more severe attacks such as:
- Phishing
- Session hijacking
- Cross-Site Scripting (XSS)

## Mitigation

- Proper input validation
- Output encoding
- Use of secure templating engines

