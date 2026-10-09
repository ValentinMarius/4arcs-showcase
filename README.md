# 4arcs-showcase
A mobile app that helps you build lasting habits through season-long personal contracts.

> Source code is private. This repository is a showcase of the product, the architecture and my role in building it.

## The idea

Users sign a personal contract with a set of daily tasks and commit to it for one or more seasonal "arcs". Each arc follows the real calendar season (winter, spring, summer, autumn), so the commitment always matches the time of year. The app tracks streaks, progress and achievements, and lets friends keep each other accountable.

## Main features

- **Contracts:** pick a preset difficulty level or build a custom contract from a habit library; choose 1 to 4 arcs.
- **Season-aligned arcs:** the first arc is shortened to end with the current real season; later arcs follow real season lengths (including leap years).
- **Daily view:** today's tasks, streak flame, focus timer and an animated progress visual.
- **Stats and badges:** progress over time and achievements.
- **Social feed:** friends' progress, streaks and reminders.
- **Shareable achievements.**

## Tech stack

React Native · Expo · TypeScript · Expo Router · Zustand · AsyncStorage · Jest · Firebase (planned) · RevenueCat (planned)

## What I built

- Wrote the full product documentation: feature spec, market analysis, roadmap, technical requirements and monetization model.
- Designed a local-first architecture, organized by feature, with business logic isolated from the UI.
- Implemented the season/arc calculation, progress computation and contract naming rules, covered by 130+ automated tests.
- Adapted the UI for both iOS and Android, including platform-specific components.
- Worked with an AI-assisted workflow (Claude Code): I wrote detailed specs, reviewed the output and tested every step.

## Status

MVP in development.
