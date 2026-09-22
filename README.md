## Ravindra Yadav

QA architect. I build the tooling that lets AI agents write, heal and run tests against
enterprise systems — Salesforce and Microsoft Dynamics, where the UI shifts several times a
year and a suite is only ever as reliable as its worst locator.

The interesting problem isn't getting a model to generate a test. It's everything around that:
knowing what to generate it against, proving it's correct before it reaches a pipeline,
repairing it when the application moves, and explaining why it failed when it does.

### What I work on

**AI test authoring** — generating executable tests from live system metadata rather than from
a model's memory of an API. The agent reads the real project and the real org, then writes
against what's actually there.

**AI self-healing** — locators that repair themselves when the application changes underneath
them. The hard part isn't finding a replacement element, it's deciding when *not* to: a heal
that silently retargets the wrong field turns a caught regression into a passing test.

**Agentic tooling for test frameworks** — exposing an automation framework to LLM agents over
MCP, so an assistant can inspect a project, generate artifacts, and validate its own output
inside one loop instead of handing a human a plausible-looking guess.

**Component discovery for dynamic UIs** — deriving stable page objects from modern component
frameworks, low-code screens and industry-specific components, where markup is generated at
runtime and conventional selectors rot on contact.

**Deterministic gates around non-deterministic generation** — rule-based validation and quality
scoring at every level of a test hierarchy. Generation is probabilistic; the gate in front of
it shouldn't be. This decides whether AI-authored tests are an asset or a new category of flake.

**Automated failure triage** — turning a wall of red into a ranked root-cause list, so the first
question after a failed run stops being "which of these 200 are real?"

**Release-impact analysis** — reading vendor release notes as a diff against an existing suite:
what changed in the rendered UI, which patterns break, what it costs to fix before it lands.

**Pipeline and orchestration** — headless runs, build-tool integration, artifact and result
reporting into quality dashboards, and the configuration management that keeps it reproducible
across environments.

**AI in the daily workflow** — MCP servers, agent skills and small CLIs for the work around the
work: triage, documentation, release review, repo chores. Most of the compounding gain isn't in
one big AI feature, it's in twenty utilities that each remove ten minutes.

**Agentic content pipeline** *(side project)* — research, draft, human approval gate, publish,
on scheduled GitHub Actions with the approval step deliberately non-optional. Built to find out
where agentic workflows break when nobody's watching. They break at the gates.

### Tech

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)

**Platforms**
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square)
![MS Dynamics 365](https://img.shields.io/badge/MS%20Dynamics%20365-002050?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square)

**AI & agents**
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Anthropic API](https://img.shields.io/badge/Anthropic%20API-191919?style=flat-square&logo=anthropic&logoColor=white)

**Test & automation**
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)
![Appium](https://img.shields.io/badge/Appium-662D91?style=flat-square&logo=appium&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**CI/CD & infra**
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Apache Ant](https://img.shields.io/badge/Apache%20Ant-A81C7D?style=flat-square&logo=apacheant&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)

**Data**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square)

**Source & delivery**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=flat-square&logo=trello&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=flat-square)

### Elsewhere

[Medium](https://medium.com/@ravindra-yadav) ·
[LinkedIn](https://www.linkedin.com/in/ravindray/) ·
[sdet.ravi@gmail.com](mailto:sdet.ravi@gmail.com)
