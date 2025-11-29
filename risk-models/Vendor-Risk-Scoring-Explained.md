Vendor Risk Scoring Explained

This document explains how to evaluate a vendor using a structured risk scoring model. Vendor Risk Analysts use this process to determine the level of risk a vendor introduces and whether additional controls or remediation are needed before approval.

A scoring model creates consistency, repeatability, and defensible decision making. This is essential for both onboarding and continuous monitoring.

The Risk Scoring Framework

Vendor risk is evaluated by combining two primary factors

Likelihood
The chance that a security issue or failure will occur

Impact
The severity of harm that would result if an issue occurred

These two factors form a simple rating system that determines the vendor’s overall risk score.

Likelihood Rating

Likelihood represents how probable it is that a vendor’s controls could fail or that a security incident could occur.
Analysts consider elements such as
• maturity of the vendor’s controls
• past incidents
• gaps found during assessments
• complexity of the environment

Likelihood is commonly rated on a scale from One through Five
• One is Very Low likelihood
• Two is Low
• Three is Moderate
• Four is High
• Five is Very High

Impact Rating

Impact represents the degree of harm the organization would experience if the vendor failed or suffered a breach.
Impact considers
• sensitivity of data shared with the vendor
• operational dependency
• financial exposure
• regulatory exposure
• potential reputational harm

Impact is also rated on a scale from One through Five
• One is Very Low impact
• Two is Low
• Three is Moderate
• Four is High
• Five is Very High

Constructing the Risk Matrix

A risk matrix visually combines likelihood and impact.
For example
If likelihood is Four and impact is Five, the resulting risk is considered Critical.
If likelihood is Two and impact is Two, the resulting risk is Low.

The matrix allows analysts to assign a consistent risk level to each vendor.

Vendor Tiering Levels

Once the score is calculated, vendors are placed into a tier.
A typical tiering structure looks like this

Low Risk Vendor
Minimal data exposure
Minimal operational dependency
Strong controls
No known issues

Medium Risk Vendor
Handles some sensitive or internal data
Moderate dependency
Minor control gaps may exist

High Risk Vendor
Handles sensitive, regulated, or confidential data
High dependency
Control gaps or exceptions present
Requires deeper review

Critical Risk Vendor
Handles mission critical data or systems
High regulatory exposure
Material control failures or unremediated exceptions
Requires executive review and formal approval

Using the Scoring Model in Real Assessments

When evaluating a vendor, an analyst follows this process

One
Review security evidence such as SOC Two reports, questionnaires, and policies

Two
Identify control strengths and weaknesses

Three
Assign a likelihood score based on maturity and gaps

Four
Assign an impact score based on data sensitivity and business dependency

Five
Combine the scores to produce the final risk rating

Six
Document required remediation if gaps exist

Seven
Decide whether the vendor is approved, conditionally approved, or rejected

Example Scenario

A vendor processes confidential customer data.
Impact is rated as Five because a breach would cause significant harm.
The vendor has a SOC Two Type Two report but contains an access review exception.
Likelihood is rated as Three because controls are generally mature but contain weaknesses.

Final score
Likelihood Three combined with Impact Five results in a High risk vendor that requires a remediation plan before approval.

Summary

A Vendor Risk Scoring Model provides a consistent and defensible method for evaluating third party security. By combining likelihood and impact, analysts can determine risk levels, prioritize remediation, and support business decisions with clear justification. This scoring model is a foundational part of the vendor risk management lifecycle.
