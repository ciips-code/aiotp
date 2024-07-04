## Privacy Policy:

The solution is based on two open-source solutions: OpenEMR for electronic medical records, and Jitsi Meet for video consultations.

**OpenEMR:** OpenEMR is an open-source electronic medical record and medical practice management software. OpenEMR’s privacy policy highlights its commitment to privacy protection and compliance with privacy regulations such as HIPAA. It focuses on the security of patient information and describes how data is managed within the system. It is licensed under CC 3.0 BY1 for a detailed evaluation of privacy and HIPAA compliance.

**Jitsi (meet.jit.si):** Jitsi is an open-source video conferencing solution. The privacy policy of meet.jit.si, last updated on August 21, 2023, describes how 8x8, Inc., the primary contributor to the Jitsi.org video conferencing solution, processes personal information to provide the meet.jit.si service. This policy covers what personal information is processed and why, how this information is used, and how to contact the data protection officer of 8x8. It also ensures that they are not in the business of selling personal information to third parties and that they use the information to deliver and improve the meet.jit.si service.

## Security and Encryption:

Regarding encryption and security points, each of the software includes the following features:

**OpenEMR** provides several security measures to protect patient data and comply with regulations such as HIPAA. Some of the security features include:

* Document encryption: OpenEMR uses the PHP mcrypt library for document encryption and decryption.
* Secure passwords: The use of strong and unique passwords is recommended, as well as password expiration.
* Multi-factor authentication: For an additional layer of security.
* Network and server configurations: It is suggested to open only port 443 (https) and consider a firewall that only allows traffic through this port.
Apache hardening: It is recommended to allow only https and disable direct access to certain directories.

**Jitsi Meet** is a video conferencing solution that also focuses on the security and privacy of its users. The security features include:
* End-to-end encryption (E2EE): Jitsi Meet offers E2EE as an additional layer of security over the always-present transport encryption.
* Ephemeral rooms: Meeting rooms only exist while the meeting is active, meaning there is no connection to previous meetings that may have had the same name.
* Room name generator: To prevent unwanted access, randomly generated room names that are difficult to guess are used.
* Browser support: End-to-end encryption is available in certain browsers, but not all.
