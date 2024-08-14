---
layout: default
title: How to check a digital certificate
parent: Legal and Security
nav_order: 2
---

Now that we are eSigning documents and receiving eSigned documents, it is important to know how to verify that a Digital Signature is valid.

**Please note that the steps below to verify a digital certificate are the same for a document signed using iSign or any other valid platform to electronically sign (DocuSign for instance). You might be interested to check a certificate that has been signed by a partner using another solution.**

**Table of contents:**
- [Responsability](#item-one)
- [Key Points](#item-two)
- [Advanced eSignature - How to verify a Digital signature?](#item-three)

<!--headings-->
<a id="item-one></a>
# Responsibility

The person representing ICRC in a contract, has to ensure the signatories (External party) identify and has all power of signature for this external party (Register of Commerce). If unsure contact OCLA.

When ICRC Staff signs a contract with an electronic signature software different from ICRC's iSign, it is ICRC Staff who signs the contract to ensure the contract complies with legal aspect, with support of OCLA.

<a id="item-two></a>
# Key points

- Digital signing is a cryptographic process. A timestamp and a unique number are assigned to a document, once signed.
- Digital certificate applies to the entire document.
- Digital certificate vary depending on the type of Electronic Signature (Basic, Advanced or Qualified).
    - Basic eSignature : no certificate.
    - Advanced eSignature : Digital certificate corroborate the signer identity, validation the signature and the fact that the document has not changed.
    - Qualified eSignature : Digital certificate is granted by a Third party (TSP), the corroboration of the signer identity is regulated.
- The process to verify the Digital signature is the same when the document is signed using our internal platform (iSign/OneSpan Sign) or if the document is issued from another platform proposed by an external partner (DocuSign, Swiss Sign, Adobe...).
- Duration of the validity of the Digital certificate is not a point/ a signature has to be valid at the moment of the signing process (a person's role in a company might change/what matters are the responsibilities of the person at the time of the signature).

<a id="item-three></a>
# Advanced eSignature - How to verify a Digital signature?

To make sure the Advanced Signature applied on the document is valid, you need to:

1\. Verify and confirm the identity of the person who is signing the document and his/her ability to sign it. Are you sure the email you have is the correct one? Is this person authorized to sign your document?
2\. Then verify the Digital certificate (see below process):
    - Check that document has not been changed.
    - Check that the signature is valid.

**Step 1**

- Open your Pdf document.
- Click on 'Signature Panel' button to access the information relative to the Digital signature and the certificate.

Note: in the left panel, the number of REV (stands for Revisor) corresponds to the number of signers in the document. A green or Red mark indicate if the signature is valid or not.

<img src="../media/How to check a digital certificate/Access_Signature_panel.png"
title="Access signature panel" width="800" />

**Step 2**

- In the left panel, click on the arrow beside the 'Rev' you want to consider displaying the information relative to his/her signature.
- Check on the Signature & signer's validity.
- Click on certificate details for more details.

<img src="../media/How to check a digital certificate/Signature_panel_details.png"
title="Signature panel details" width="800" />

**Step3**

- The certificate details give more information, in particular on the Certification Authority (CA).

<img src="../media/How to check a digital certificate/Certificate_details.png"
title="Certificate details" width="800" />

- The Tab "Trust" displays a visual icon with 2 green "checks".
- This screenshot shows the 2 required "green checks".

<img src="../media/How to check a digital certificate/Trust_details.png"
title="Trust details" width="800" />