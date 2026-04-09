# Commercial Sales Tools

Interactive, self-serve tools built for the dbt Labs commercial team. Each tool is a self-contained HTML file — no setup needed.

**[Browse all tools →](https://sturdy-adventure-l4rvrye.pages.github.io/)**

## Tools

| Tool | Category | Description |
|---|---|---|
| [Cost of Doing Nothing](./cost-of-doing-nothing/) | Calculator | Quantify the business impact of inaction — helps prospects understand the real cost of delaying a dbt investment |

## Structure

```
commercial-sales-tools/
├── index.html                    # landing hub
├── cost-of-doing-nothing/
│   └── index.html
└── README.md
```

## Usage

Open the live link above, or download any `index.html` and open it directly in a browser.

## Adding a New Tool

1. Create a new folder with a descriptive slug (e.g. `discovery-playbook/`)
2. Add a self-contained `index.html` inside it
3. Update `index.html` at the root — remove the `coming-soon` class from the relevant card and add an `href`
4. Push to the `gh-pages` branch
