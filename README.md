# Cloudflare-Email-Decoder
A Python tool that decodes Cloudflare-protected email addresses stored in Excel files. It reads encoded values from the encoded_email column, applies XOR decoding, removes invalid characters, and saves a new sheet with a decoded_email column. Useful for restoring hidden emails for reporting and data processing.

Key Features

✔ Decodes Cloudflare-protected email addresses using XOR-based reverse encoding
✔ Works on Excel sheets automatically by reading the encoded_email column
✔ Generates a new decoded_email column with restored email values
✔ Removes unprintable / invalid characters to ensure Excel compatibility
✔ Supports real-world datasets for data processing, analytics, reporting, and CRM imports

🔧 How It Works

Reads the input Excel file using pandas

Extracts hex-encoded email strings from the encoded_email column

Applies Cloudflare XOR decoding logic

Cleans output to remove non-printable characters

Exports a new Excel file with decoded results
