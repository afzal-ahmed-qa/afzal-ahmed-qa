### Hi, I'm Afzal

I'm a QA engineer with more than ten years in IT delivery and quality assurance, most recently
testing web, SaaS and AI-enabled products: test design, exploratory testing, bug reports and
working with developers in Jira. Over the past while I've been moving into API testing and UI
automation, and these are the projects that show where I am now.

**[toolshop-playwright-framework](https://github.com/afzal-ahmed-qa/toolshop-playwright-framework)**
A Playwright and TypeScript framework for a realistic web shop with customers, admins and a
four-step checkout: 84 UI, API, accessibility and visual tests. Typed API clients check every
response against a schema, and UI results are verified through the API. CI starts its own copy of
the shop in Docker, runs the suite in four shards and publishes [one merged report](https://afzal-ahmed-qa.github.io/toolshop-playwright-framework/).
It found 17 documented defects, including product creation without login and, in the shop's
bug build, password hashes readable by any customer.

**[playwright-typescript-e2e-framework](https://github.com/afzal-ahmed-qa/playwright-typescript-e2e-framework)**
UI and API tests for demoqa.com with Playwright and TypeScript, using the Page Object Model.
End-to-end user journeys, API-based test setup, accessibility and visual checks. It runs in
GitHub Actions and publishes a [report with a video of every test](https://afzal-ahmed-qa.github.io/playwright-typescript-e2e-framework/).

**[playwright-saucedemo-cross-browser](https://github.com/afzal-ahmed-qa/playwright-saucedemo-cross-browser)**
The full buying journey of a web shop, from login to order confirmation, tested with Playwright and
TypeScript on Chrome, Firefox and Safari on an iPhone. Checks the item total, tax and order total
against the shop's own prices, and keeps four defects as expected-failure tests, including a
checkout where the customer cannot finish the order. Each browser runs as its own CI job and the
results are merged into [one report](https://afzal-ahmed-qa.github.io/playwright-saucedemo-cross-browser/).

**[toolshop-api-tests-postman](https://github.com/afzal-ahmed-qa/toolshop-api-tests-postman)**
API tests for a realistic online shop with JWT login, customer and admin roles, a cart and a real
checkout. Covers the account lifecycle, purchase flow and access control, and found seven defects,
including products that can be edited without logging in and customers who can mark their own
orders as completed. [Latest report](https://afzal-ahmed-qa.github.io/toolshop-api-tests-postman/).

**[petstore-api-tests-postman](https://github.com/afzal-ahmed-qa/petstore-api-tests-postman)**
A Postman collection for the Swagger Petstore covering all 20 endpoints: full CRUD flows, negative
and data-driven tests, run daily with Newman. It found that the API accepts any password and
returns users' passwords in plain text. [Latest report](https://afzal-ahmed-qa.github.io/petstore-api-tests-postman/).

**[manual-test-plans-ecommerce](https://github.com/afzal-ahmed-qa/manual-test-plans-ecommerce)**
Test strategy, UI and API test plans, 88 test cases, a traceability matrix and defect reports for
an e-commerce site. Every case was executed; one of the bugs lets a negative quantity give the
cart a negative total.

Tools I use day to day: Playwright, TypeScript, Postman and Newman, Git, GitHub Actions, Docker, Chrome
DevTools and axe for accessibility. For tracking work and defects I've used Jira, Azure DevOps,
ClickUp, Asana and Confluence.

My CV is here: [Afzal_Ahmed_QA_CV.pdf](cv/Afzal_Ahmed_QA_CV.pdf). I'm available for remote QA work with
European and US teams, freelance or full-time. You can reach me at
afzal.ahmed0913@gmail.com or on [LinkedIn](https://www.linkedin.com/in/afzal-ahmed-217395b3/).
