# Phishing Awareness Simulation Lab

## Project overview

This project documents an **authorized security-awareness simulation** built with GoPhish in a controlled lab environment.

The purpose was to understand the administrative workflow behind phishing-awareness testing: preparing a campaign, configuring training content, defining test recipients, launching the simulation, and reviewing results from a defensive/security-awareness perspective.

> **Scope:** Use only with systems and recipients you own or are explicitly authorized to test. Do not collect or retain real credentials.

## Technologies

- GoPhish
- Railway
- Windows 11
- web-based campaign administration

## What I configured

### 1. Deploy the GoPhish lab

I deployed a GoPhish instance through Railway and verified that the administrative interface was reachable.

![GoPhish deployment](https://i.imgur.com/yvPL5pK.png)

### 2. Access the administrative interface

I retrieved the lab administrator credentials from the deployment output and signed in to the GoPhish management console.

![GoPhish admin interface](https://i.imgur.com/imyZ4Ns.png)

### 3. Prepare awareness-campaign components

I configured the components required for an internal simulation:

- test users/groups
- an awareness email template
- a sending profile for the authorized lab
- a training/landing page used for simulation purposes

![Campaign configuration](https://i.imgur.com/l4iMdw0.png)

![Campaign configuration](https://i.imgur.com/yJl0pLe.png)

![Campaign configuration](https://i.imgur.com/EUpffFh.png)

![Campaign configuration](https://i.imgur.com/UAMogAB.png)

### 4. Launch the controlled simulation

I assembled the configured components into a GoPhish campaign and launched the test against the authorized target group.

![Campaign launched](https://i.imgur.com/Egqa9Vz.png)

## Defensive lessons

This lab reinforced several security concepts:

- phishing simulations require explicit authorization and defined scope
- sending infrastructure and domain reputation affect message delivery
- awareness testing should minimize collection of sensitive data
- simulation results are most useful when paired with user education and measurable follow-up
- security teams should document scope, approvals, retention, and remediation before running exercises

## Production considerations

A mature awareness program should include:

- written authorization and rules of engagement
- test accounts or non-sensitive training inputs
- privacy/legal review where required
- secure handling and short retention of simulation data
- controlled sender infrastructure
- SPF, DKIM, and DMARC awareness
- metrics such as reporting rate and training completion
- remediation and repeat testing

## Portfolio takeaway

This project demonstrates familiarity with security-awareness tooling and the operational considerations surrounding authorized phishing simulations. It is presented as a **defensive training lab**, not as a credential-harvesting or unauthorized social-engineering exercise.
