# IniClaw Policies

This directory contains security policies for the IniClaw sandbox.

- `openmaic.yaml`: The default policy for OpenMAIC agents. It allows network access to necessary LLM providers and OpenMAIC services, and grants read/write access to the `.classroom-cache` directory.

To apply a policy, use:
`nemoclaw <sandbox-name> policy-add openmaic`
