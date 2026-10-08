# runsweep-demo

Fire-drill target for [runsweep](https://github.com/dmitriy86it/runsweep).

The workflow installs a harmless package (`is-number@7.0.0`) and uses pinned actions so that
`examples/drill.yaml` in runsweep can pretend they were compromised. The repository secrets
`DEMO_NPM_TOKEN` and `DEMO_SLACK_WEBHOOK` hold fake values; nothing here is real.
