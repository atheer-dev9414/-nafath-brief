version: NAFATH-V3
Track: Cybersecurity

## Overview
A government entity plans to add an AI chat assistant to its mobile app so citizens can ask questions about public services. Software engineering provides a stable API and clear versioning rules as the assistant evolves. Artificial intelligence helps the assistant interpret questions and retrieve reliable information before generating responses. Mobile development ensures that citizens can access the service through a secure and usable app. Networking supports communication between the app, servers, and connected systems as demand grows. Cybersecurity protects the assistant and its users from malicious inputs, data exposure, and other threats. Data management determines how chat logs are stored, protected, and used responsibly. These fields depend on one another: a helpful assistant must be accurate, accessible, secure, and reliable. Cybersecurity is especially important because the assistant may face direct and indirect prompt-injection attacks that attempt to manipulate its behaviour.

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
IPv4 and IPv6 are two versions of the Internet Protocol used to identify devices and route data across networks. IPv4 uses 32-bit addresses, while IPv6 uses 128-bit addresses, providing a much larger pool of unique addresses. As the number of connected phones, computers, smart appliances, and other devices increases, IPv6 helps meet the growing demand for IP addresses and supports the continued expansion of the Internet.

Resource: IPv6 FAQ - Internet Society - https://www.internetsociety.org/deploy360/ipv6/faq/




## Cybersecurity
Prompt injection occurs when malicious instructions attempt to manipulate an AI system into ignoring its intended rules. Direct prompt injection comes from instructions entered by a user, while indirect prompt injection may be hidden in external content, such as a document or webpage processed by the system. Risk can be reduced by treating retrieved content as untrusted, limiting the AI’s access to sensitive data and tools, and validating actions before they are carried out.

Resource: OWASP Top 10 for Large Language Model Applications - Prompt Injection - https://genai.owasp.org/llmrisk/llm01-prompt-injection/
## Data
Anonymization and pseudonymization are methods used to reduce the risk of identifying people from data. Anonymization removes identifying information so that individuals can no longer be identified by means reasonably likely to be used. Pseudonymization replaces direct identifiers with codes or alternative values, but additional information may still allow a person to be identified. Under the GDPR, truly anonymized data falls outside its scope, while pseudonymized personal data generally remains protected.

Resource: What is personal data? - Information Commissioner’s Office - https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/personal-information-what-is-it/what-is-personal-data/


## Misconception in My Track
A common misconception is that prompt injection only happens when a user directly types malicious instructions into an AI assistant. In reality, indirect prompt injection can also occur when malicious instructions are hidden in external content, such as webpages or documents that the system processes. This means that even ordinary-looking content may contain instructions intended to manipulate the model. Treating retrieved content as untrusted is therefore important when designing secure AI applications.

Resource: LLM01: Prompt Injection - OWASP Gen AI Security Project - https://genai.owasp.org/llmrisk2023-24/llm01-24-prompt-injection/




## Open Question
How can an AI assistant distinguish legitimate information from hidden malicious instructions in external content while still providing useful answers?

