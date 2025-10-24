# new-project

This repository was created for Jira ticket PROM-42164.

## Step-by-step (for developers)

1) Clone and enter:
   git clone <REPO_URL>
   cd new-project

2) Create/switch to development branch:
   git switch -c development

3) Make changes and commit with the Jira key and Smart Commit:
   git add .
   git commit -m "PROM-42164 #comment Update README with setup steps"

4) Push the branch:
   git push -u origin development

5) Create a Pull Request from `development` to `main`, get review, and merge.

## Smart Commit examples (Jira)
- PROM-42164 #comment Add detailed setup steps
- PROM-42164 #time 30m #comment Wrote README
- PROM-42164 #done Merge development into main
