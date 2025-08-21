# UI Automation

[![n8n](https://img.shields.io/badge/built%20with-n8n-3ebd70.svg)](https://n8n.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Table of Contents

- [Project Overview](#project-overview)
- [Motivation](#motivation)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Workflow Details](#workflow-details)
- [License](#license)
- [Author & Contact](#author--contact)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

**UI Automation**  
An automated n8n workflow that runs every minute to convert the current date and time into a human-readable, precisely formatted text string using OpenAI’s GPT-4.1-mini model, then sends the converted text to an external HTTP endpoint via POST request.

---

## Motivation

Automating date and time formatting in human-friendly wording is useful for logging, reporting, or notifications where precise formats and timezone considerations matter. This workflow leverages AI to format date-time strings strictly as defined, ensuring consistent output.

---

## Features

- Scheduled trigger running every 1 minute
- Retrieves current date & time in Asia/Kolkata timezone
- Uses OpenAI GPT model to convert date-time to a fully formatted textual representation 
- Sends converted text data to a custom HTTP endpoint
- Strict formatting: long dash, ordinal suffixes, 12-hour format with seconds, IST timezone

---

## Prerequisites

- Active n8n instance (Cloud or self-hosted)
- Node.js for local n8n setup
- OpenAI API key with access to GPT-4.1-mini
- Access to an HTTP endpoint that accepts POST requests

---



