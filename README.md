# github action concurrency demo

demo concurrency usage

## Demo items

- flow with main branch
- flow with the PR process
- flow wiht the PR branch updates
- flow with the workflow_dispatch events
- `cancel-in-progress: true` vs `cancel-in-progress: ${{github.event_name == 'pull_request'}}` etc

## test PR progress

## references
blog, https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions#concurrency
documentation, https://github.blog/changelog/2021-04-19-github-actions-limit-workflow-run-or-job-concurrency/
