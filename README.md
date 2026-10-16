# devops-team-practice

A practice copy of [devops-tasks-api](https://github.com/agl-learn-examples/devops-tasks-api), the running example of the DevOps track on [agentlabs learn](https://learning.myagentlabs.ai).

It is used by **Course 3, Lesson 8, "Retell, reflect, practise"**: two clones ("you" and a partner) each change the same line of `GET /tasks` on their own branch, the partner's pull request is squashed and merged first, and the other branch is rebased on `origin/main`, resolved, pushed with `--force-with-lease`, merged, and tagged `v0.2.0`.

The lesson runs here, not in the track repo, so the recording starts from a clean, known main while other lessons change the track repo. The real code lives in **https://github.com/agl-learn-examples/devops-tasks-api**.

## Run it

    python3 -m venv .venv
    . .venv/bin/activate
    pip install -r requirements.txt
    pytest -q
