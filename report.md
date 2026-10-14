# Cyber Security Internship — Task 2
## Phishing Email Analysis Report
### 1. Objective
To identify common phishing indicators in a simulated suspicious email and document the observations.
### 2. Sample Information
- Sample type: Fictional training email
- Sender: Account Security
- Subject: URGENT! Your account will be suspended
- Analysis method: Manual inspection of the sender address, subject, message body and displayed URL.
### 3. Phishing Indicators Identified
#### Indicator 1: Lookalike Sender Spelling
The sender address contains `paypaI.example`, using a capital I that resembles a lowercase l.
**Observation:** The spelling may be intended to resemble a familiar brand. The sender's identity has not been verified.

#### Indicator 2: Urgent Language
The subject uses the word "URGENT" and the message threatens suspension within 24 hours.
**Observation:** This creates time pressure and may encourage the recipient to act without verifying the request.

#### Indicator 3: Unverified Link
The email displays `https://account-verify.example.com`.
**Observation:** The destination has not been verified as belonging to the organization represented in the message. The link was not opened.

#### Indicator 4: Generic Greeting
The email begins with "Dear Customer."
**Observation:** This is a contextual observation, not proof of phishing, because legitimate organizations also use generic greetings.

#### Indicator 5: Missing Original Email Headers
The sample contains only the visible email text and does not include original delivery headers.
**Observation:** Sender routing and SPF, DKIM and DMARC authentication results could not be examined.

### 4. Findings Summary
The fictional sample contains several characteristics commonly associated with phishing: lookalike sender spelling, urgency, an unverified verification link and a generic greeting.
These characteristics justify caution, but the sample does not establish that a real email was sent by a malicious actor.

### 5. Limitations
- The email is a simulated training example.
- No original email headers were available.
- The sender's identity was not independently verified.
- No live URL or attachment was tested.
- No claim is made that SPF, DKIM or DMARC failed.

### 6. Safety Recommendations
1. Do not click suspicious links or open unexpected attachments.
2. Verify account-related requests using the organization's independently obtained official website or contact details.
3. Report suspicious emails to the appropriate security team or email provider.
4. Preserve evidence while protecting personal and confidential information.

### 7. Conclusion
This exercise demonstrates how to recognize and document potential phishing indicators. In a real investigation, the conclusions should be supported by original email headers and additional independent evidence.
