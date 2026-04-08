# Xinyi Li

This repository contains my coursework for Responsible AI / GenAI assignments.

## Week 4 Project Plan

The main file for this milestone is:

- [project_plan.md](./project_plan.md)

## Project Summary

My planned final project is a **policy-grounded customer support reply assistant** for a B2B SaaS workflow.

The idea is to help a frontline support agent:

- read an incoming support ticket
- retrieve the most relevant internal policy guidance
- draft a first-pass customer reply
- recommend whether the case should be escalated

The system is intentionally narrow in scope so it can be evaluated seriously and compared against a simpler baseline.

## Planned App

The final artifact is planned as a small **Streamlit app** where a user can:

1. paste a support ticket
2. provide a small amount of account context
3. view retrieved policy evidence
4. compare a baseline output against a safer, policy-grounded version

## Notes

- Synthetic or public data only
- No secrets, API keys, or personal customer data will be committed
- The project is designed with human review boundaries for risky cases such as legal, security, and refund-exception scenarios
