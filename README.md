**PORTFOLIO ASSESSMENT**

**Title: Comparative Study of Multi-Factor Authentication Methods**

**1. INTRODUCTION:**

Multi-Factor Authentication (MFA) is a security method where the user has to provide two or more authentication factors before getting access. This makes the account more secure than using only a password.
The three main authentication factors are something you know, something you have, and something you are. There are different MFA methods available, and each one has its own level of security, advantages, limitations and uses. In this portfolio, different MFA methods are compared based on these factors.

**2. OBJECTIVES:**

•	To understand the basic concept of Multi-Factor Authentication. 

•	To study different MFA methods. 

•	To compare the security of different MFA methods. 

•	To understand the advantages and limitations of each method. 

•	To study where different MFA methods are used. 

**3. MFA METHODS:**

**a)	SMS-Based OTP:**

**Working:**

In this method the user enters their username and password. Then, a one-time password (OTP) is sent to their registered mobile number. The user enters this OTP to complete the login.

**Advantages:**

•	Easy to use. 

•	Simple to set up. 

•	Works with most mobile phones.


**Limitations:**

•	Can be affected by SIM-swapping attacks. 

•	Can be targeted through phishing.

•	Depends on mobile network availability.

**Applications:**
Online banking, e-commerce websites and other web services.

**b)	Email OTP:**

**Working:**

After entering the login details, a verification code is sent to the user's registered email address. The user enters the code to verify the login.

**Advantages:**

•	Easy to implement.

•	Does not require any extra hardware. 

•	Familiar and convenient for most users.

**Limitations:**

•	Depends on the security of the email account. 

•	Requires an internet connection. 

•	The OTP may sometimes be delayed.

**Applications:**
Web applications, educational portals and account verification.

**c)	Authenticator App / TOTP:**

**Working:**

An authenticator app generates a temporary code based on time. The code changes after a short period, and the user enters the current code while logging in.

**Advantages:**

•	More secure than SMS OTP. 

•	Does not need a mobile network to generate the code. 

•	Works even when SMS service is unavailable.

**Limitations:**

•	Requires an authenticator app.

•	Problems may occur if the device is lost. 

•	The user needs to keep the device available for login.

**Applications:**
VPNs, enterprise systems, cloud services and university systems.

**d)	Push Authentication:**

**Working:**

When someone tries to log in, a notification is sent to the user's registered smartphone. The user can check the request and select Approve or Reject.

**Advantages:**

•	Very convenient to use.

•	Provides quick authentication.

•	Users can approve or reject the login directly from the phone.

**Limitations:**

•	Can be misused through MFA fatigue attacks. 

•	Requires a smartphone and internet connectivity. 

•	Unexpected notifications may confuse users.

**Applications:**
Enterprise systems, cloud services and remote access.

e)	Hardware Security Token:

**Working:**

A physical security token is used during login. It can generate an OTP or use cryptographic authentication to verify the user's identity.

**Advantages:**

•	Provides strong security. 

•	Useful for high-security accounts. 

•	Less dependent on mobile networks or email services.

**Limitations:**

•	The token can be lost or damaged. 

•	It may have additional cost. 

•	Replacement and recovery may be required if the token is lost.

**Applications:**
Banking, administrator accounts and high-security systems.

**f)	Biometric Authentication:**

**Working:**

The user provides a biometric feature such as a fingerprint, face, iris or voice. The system compares it with the previously registered biometric information and allows access if it matches.

**Advantages:**

•	Fast and convenient.

•	No OTP needs to be remembered.

•	Easy to use for frequent authentication.

**Limitations:**

•	Can create privacy concerns. 

•	False acceptance or rejection can sometimes occur. 

•	Biometric information cannot be changed easily if compromised.

**Applications:**
Smartphones, banking applications and physical access systems.

**g)	FIDO2 / WebAuthn / Passkeys:**

**Working:**

In these methods, public-key cryptography is used to check and confirm the user's identity. The user can confirm the login using a device PIN or biometric authentication.

**Advantages:**

•	Provides strong protection against phishing.

•	Can be used for password less login. 

•	Provides strong cryptographic authentication.

**Limitations:**

•	Requires compatible devices and services. 

•	Recovery can be difficult if the device is lost.

•	Availability may depend on whether the service supports passkeys or FIDO2.

**Applications:**
Banking, cloud services, enterprise systems and password less login.

**4. COMPARATIVE ANALYSIS:**

<table>
<tr>
<th>MFA Method</th>
<th>Security</th>
<th>Convenience</th>
<th>Main Difference</th>
</tr>

<tr>
<td>SMS OTP</td>
<td>Medium-Low</td>
<td>High</td>
<td>Simple and widely available</td>
</tr>

<tr>
<td>Email OTP</td>
<td>Medium-Low</td>
<td>High</td>
<td>Depends on email security</td>
</tr>

<tr>
<td>Authenticator / TOTP</td>
<td>Medium-High</td>
<td>Medium</td>
<td>Uses time-based codes</td>
</tr>

<tr>
<td>Push Authentication</td>
<td>Medium-High</td>
<td>Very High</td>
<td>Quick approval</td>
</tr>

<tr>
<td>Hardware Token</td>
<td>High</td>
<td>Medium</td>
<td>Uses a physical device</td>
</tr>

<tr>
<td>Biometrics</td>
<td>High</td>
<td>Very High</td>
<td>Uses personal characteristics</td>
</tr>

<tr>
<td>FIDO2 / Passkeys</td>
<td>Very High</td>
<td>Very High</td>
<td>Strong phishing protection</td>
</tr>

</table>

From this comparison, SMS and Email OTP are easier to use but have lower security. Authenticator apps give a good balance between security and convenience. Hardware tokens and FIDO2/passkeys are better choices when stronger security is needed.

**5. FINDINGS:**
   
The comparison shows that every MFA method has its own strengths and weaknesses. SMS and Email OTP are simple, authenticator apps provide better security, and hardware tokens give strong protection. Biometrics are convenient, while FIDO2 and passkeys provide strong protection against phishing.

**6.TESTING AND EVIDENCE:**

**Figure 1:** Authenticator App / TOTP

**Figure 2:** Biometric Authentication

**Figure 3:** Passkey Authentication

**7. REFLECTION:**

Through this portfolio, I understood that MFA is not limited to OTP verification. I learned that different methods provide different levels of security and convenience. I also understood why phishing-resistant methods such as FIDO2 and passkeys are useful for high-security applications.

**8. CONCLUSION:**

Multi-Factor Authentication provides better security by using more than one authentication factor. Different methods offer different levels of security and convenience.
SMS and Email OTP are simple options, while FIDO2, passkeys and hardware tokens provide stronger protection. So, the MFA method can be chosen depending on the security required and the type of application.

**9. REFERENCES:**

1.Grassi, P. A., Fenton, J. L., Newton, E. M., et al. (2020). Digital identity guidelines: Authentication and lifecycle management. NIST.

2.Grassi, P. A., Garcia, M. E., & Fenton, J. L. (2017). Digital identity guidelines. NIST.

3.World Wide Web Consortium. (2021). Web Authentication: An API for accessing public key credentials—Level 2. W3C.

4.World Wide Web Consortium. (2026). Web Authentication: An API for accessing public key credentials—Level 3. W3C.

5.Grassi, P. A., Perlner, R., Newton, E. M., et al. (2017). Digital identity guidelines: Authentication and lifecycle management. NIST.



