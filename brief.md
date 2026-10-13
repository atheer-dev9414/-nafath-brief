version: NAFATH-V3
Track: Cybersecurity

## Overview
A government entity plans to add an AI chat assistant to its mobile app so citizens can ask questions about public services. Software engineering provides a stable API and clear versioning rules as the assistant evolves. Artificial intelligence helps the assistant interpret questions and retrieve reliable information before generating responses. Mobile development ensures that citizens can access the service through a secure and usable app. Networking supports communication between the app, servers, and connected systems as demand grows. Cybersecurity protects the assistant and its users from malicious inputs, data exposure, and other threats. Data management determines how chat logs are stored, protected, and used responsibly. These fields depend on one another: a helpful assistant must be accurate, accessible, secure, and reliable. Cybersecurity is especially important because the assistant processes user questions and may encounter attempts to manipulate its behaviour.

## Software
Semantic Versioning uses three numbers: MAJOR, MINOR, and PATCH. The MAJOR number increases when a change breaks compatibility with the previous API version. The MINOR number increases when new functionality is added without breaking compatibility. The PATCH number increases when backward-compatible bug fixes are released. These rules help developers communicate the impact of updates and help other systems determine whether an API change may affect their integration.

Resource: Semantic Versioning 2.0.0 - https://semver.org/
## AI
Retrieval-Augmented Generation (RAG) combines information retrieval with text generation. Before answering a question, the system retrieves relevant information from an external knowledge source and provides it to the AI model as context. This can help the model produce answers grounded in relevant evidence rather than relying only on information learned during training. RAG can reduce incorrect responses, but it does not guarantee that every answer will be accurate.

Resource: Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks - https://arxiv.org/abs/2005.11401
## Mobile
Apple’s App Transport Security (ATS) improves network security by requiring secure connection standards for supported app networking. It generally requires HTTPS connections that meet Apple’s security requirements instead of unencrypted HTTP. If an iOS app attempts to connect to an HTTP endpoint, ATS may block the connection by default unless an applicable exception is configured. Using HTTPS helps protect information exchanged between the mobile app and its server.

Resource: Preventing Insecure Network Connections - https://developer.apple.com/documentation/security/preventing-insecure-network-connections
## Networking

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
