# github action concurrency demo

demo concurrency usage

## Demo items

1. flow with main branch
2. flow with the PR process
3. flow wiht the PR branch updates
4. flow with the workflow_dispatch events
5. `cancel-in-progress: true` vs `cancel-in-progress: ${{github.event_name == 'pull_request'}}` etc

## test PR progress
### commit 2

## references
blog, https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions#concurrency
documentation, https://github.blog/changelog/2021-04-19-github-actions-limit-workflow-run-or-job-concurrency/
