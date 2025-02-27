# Customer Support Ticket Agent using PromptQL

Step 1: Clone the project

```bash
git clone git@github.com:hasura/promptql-customer-support-ticket-example.git
```

Step 2: Setup the database

```bash
cd postgres
docker compose up -d
```

Step 3: Build Hasura DDN Project

```bash
cd ddn-project
ddn supergraph build local
```

Step 4: Run PromptQL

```bash
ddn run docker-start
```