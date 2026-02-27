# AutoReviewer-Python-Security
An LLMOps-driven Python security code review assistant that analyzes PR diffs, applies security rules, and generates structured, validated vulnerability reports.
🚀 Project Overview

AutoReviewer is a Python-focused LLM-powered security review assistant designed to analyze GitHub Pull Request (PR) diffs.
The system identifies security vulnerabilities, explains associated risks, and suggests safer alternatives using a rule-enhanced LLM pipeline.

This project demonstrates core LLMOps practices, including:

PromptOps (version-controlled prompt templates + security rule injection)

JSON schema validation + correction loop (100% structured output guarantee)

Evaluation with precision/recall/F1 metrics

MLflow run tracking + prompt A/B testing

Deployment via AWS ECS / Fargate

Monitoring with CloudWatch

CI/CD with GitHub Actions

🎯 Project Goals

Build a reliable and safe LLM-based security reviewer specialized for Python.

Automate PR diff ingestion → LLM analysis → validated security findings.

Achieve stable structured outputs via schema enforcement + retry.

Evaluate system performance using a curated vulnerability dataset.

Deploy a production-like LLMOps system with monitoring & CI/CD.
