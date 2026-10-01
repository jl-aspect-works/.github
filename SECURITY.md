# JL Aspect Works Security Policy

This is the default security policy for JL Aspect Works repositories that do not provide their own policy. A repository-specific policy takes precedence, including its supported-version commitments.

## Supported code and content

Security-sensitive corrections are made on the affected repository's current development branch. Product repositories define supported release lines in their own security policies. Brand assets, shared GitHub configuration, and engineering documents do not have a separately versioned runtime support promise.

## Reporting a vulnerability

Do not post credentials, private customer data, exploit instructions, or suspected vulnerabilities in public issues or pull requests.

Use **Security → Report a vulnerability** in the affected repository when private vulnerability reporting is enabled. If that option is unavailable, contact the repository owner privately before public disclosure. This policy does not imply that private reporting is enabled in every repository; it must be verified separately in repository settings.

Include the affected repository and version/commit, reproduction steps, expected impact, and any suggested mitigation. Keep credentials and private project data out of reports; use a minimal reproduction.

Reports are evaluated for reproducibility and impact. No fixed response-time or disclosure SLA is promised.

## Verification and releases

Follow the [standing development agreement](https://github.com/jl-aspect-works/engineering/blob/main/docs/DEVELOPMENT_AGREEMENT.md) for security findings, immutable Action pins, CI, and release provenance. Releases must be produced by approved workflows; corrections use new versions/tags. Platform signing/notarization remains separately deferred unless explicitly reprioritized.
