# Digital Economics partner-change form

A customer-first, browser-only form preparation tool for an Odoo partner-of-record request.

## Use

1. Open `index.html` in a current browser, or use the deployed website.
2. Enter the customer, subscription, and partner information.
3. Download the PDF and review it. The customer must sign the blank signature area.
4. Copy the English email draft into the customer's own email, attach the signed PDF, and send it to their Odoo Account Manager.
5. Follow Odoo's requirements and wait for confirmation. This tool does not itself change the partner of record.

The new partner is fixed as **Digital Economics LLC**, **https://de.com.eg**.

## Privacy

The page has no backend, analytics, external runtime dependencies, customer-data requests, or browser storage. Entries live in the current tab's memory only. Reloading or closing the page clears them. The generated PDF is downloaded to the user's device; copied email text is placed on their clipboard. Users should handle both appropriately.

The website host receives normal page requests such as IP address and browser information, but entered form data is not sent by this application. The page's Content Security Policy blocks network connections and form submissions.

## Template and limits

Substantive form statements were transcribed from the supplied partner-of-record DOCX, correcting duplicated text and character corruption. A subscription-code field was added because the original text references that code. The customer remains responsible for accurate completion and signature. Odoo may require further documentation or its current form.

PDF generation uses bundled jsPDF and DejaVu Sans fonts. Licenses are included in `THIRD-PARTY-NOTICES.txt`. English and Arabic text are supported; review generated PDFs before submission.

No signatures, real customer records, credentials, or account-manager addresses are included in this repository.
