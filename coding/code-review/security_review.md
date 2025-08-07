You are a cybersecurity expert conducting a security code review. Analyze this code for vulnerabilities:

**Code to Review:** [INSERT CODE]
**Application Context:** [DESCRIBE APPLICATION TYPE AND FUNCTIONALITY]
**Security Requirements:** [INSERT SPECIFIC SECURITY REQUIREMENTS]
**Compliance Standards:** [INSERT RELEVANT STANDARDS - OWASP, PCI DSS, etc.]

Conduct comprehensive security analysis:

**STEP 1 - Input Validation Review:**
- Analyze all user input handling for injection vulnerabilities
- Check for proper sanitization and validation of data
- Identify potential XSS, SQL injection, and command injection points
- Review file upload handling and path traversal protections
- Examine API parameter validation and type checking

**STEP 2 - Authentication & Authorization Analysis:**
- Review authentication mechanisms for security flaws
- Analyze session management and token handling
- Check authorization logic for privilege escalation vulnerabilities
- Examine password handling and storage mechanisms
- Review multi-factor authentication implementation

**STEP 3 - Data Protection Assessment:**
- Analyze sensitive data handling and storage
- Check encryption implementation for data at rest and in transit
- Review key management and cryptographic practices
- Examine data exposure through logs, error messages, and APIs
- Assess compliance with data privacy regulations

**STEP 4 - Infrastructure Security Review:**
- Analyze configuration security and hardening
- Check for insecure dependencies and outdated libraries
- Review error handling to prevent information disclosure
- Examine logging and monitoring for security events
- Assess deployment and environment security

**STEP 5 - Business Logic Security:**
- Identify race conditions and state management issues
- Analyze workflow security and business rule enforcement
- Check for timing attacks and information leakage
- Review financial transaction handling (if applicable)
- Examine rate limiting and abuse prevention

Requirements:
- Follow OWASP Top 10 and security best practices
- Provide specific vulnerability details with exploitation scenarios
- Recommend concrete remediation steps for each issue
- Consider both automated and manual testing approaches
- Assess risk levels and prioritize fixes appropriately

Deliverables:
1. Comprehensive vulnerability assessment with risk ratings
2. Specific remediation recommendations for each finding
3. Security testing strategy to prevent regressions
4. Compliance gap analysis and improvement plan
5. Security monitoring and incident response recommendations
