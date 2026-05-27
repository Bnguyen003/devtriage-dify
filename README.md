# DevTriage

AI-powered GitHub issue triage assistant built with Dify and EdgeOne.

DevTriage helps developers and open-source maintainers analyze GitHub issues instantly using AI. Simply paste a GitHub issue URL and receive an intelligent breakdown including issue summary, severity level, suggested labels, and possible root causes.

Built for the **Dify x EdgeOne Best Practices Contest**.

---

## Why DevTriage?

Maintainers often spend hours manually reviewing GitHub issues:

* Understanding long issue reports
* Categorizing bug severity
* Assigning labels
* Identifying potential causes

DevTriage streamlines this process using an AI workflow powered by Dify and deployed globally with EdgeOne.

---

## Features

* AI-powered issue summarization
* Severity detection
* Suggested GitHub labels
* Root cause analysis hints
* Fast global deployment with EdgeOne
* Clean and lightweight UI

---

## Tech Stack

* Dify Workflow
* EdgeOne Pages & Functions
* HTML / CSS / JavaScript
* GitHub Issues API

---

## Demo

Live Demo:
https://devtriage-dify.edgeone.dev

### Sample Issues

Try these public GitHub issues:

* https://github.com/facebook/react/issues/29900
* https://github.com/vercel/next.js/issues/54157
* https://github.com/microsoft/vscode/issues/204095

---

## Screenshot

<img width="1916" height="1027" alt="image" src="https://github.com/user-attachments/assets/9d216217-28cd-4759-a93f-25bddc6cdbc9" />
<img width="1913" height="1029" alt="image" src="https://github.com/user-attachments/assets/c4a70ab1-f045-4346-80d2-13824e6028bf" />


---

## Architecture

<img width="1195" height="1600" alt="image" src="https://github.com/user-attachments/assets/1b8c4265-c356-4621-8cee-ccc7b22b5c36" />

---

## Deployment

DevTriage is deployed globally using EdgeOne Pages and Edge Functions.

### Deployment Flow

<img width="1600" height="630" alt="image" src="https://github.com/user-attachments/assets/b255db2b-dbc0-4449-b7a5-c22723c5fef1" />

---

## How It Works

1. User pastes a GitHub issue URL
2. Frontend sends request to EdgeOne Function
3. Edge Function securely calls Dify Workflow API
4. AI analyzes the issue
5. Structured triage result is returned instantly

---

## Local Development

```bash
git clone https://github.com/Bnguyen003/devtriage-dify.git
cd devtriage-dify
```

Create a `.env` file:

```env
DIFY_API_KEY=your_api_key
```

Run locally using your preferred static server.

---

## Environment Variables

| Variable     | Description           |
| ------------ | --------------------- |
| DIFY_API_KEY | Dify Workflow API Key |

---

## Future Improvements

* GitHub OAuth integration
* Automatic issue labeling
* Multi-language support
* Repository-wide analytics
* Team collaboration dashboard

---

## Built With

* Dify
* EdgeOne
* Open-source inspiration ❤️

---

## License

MIT License
