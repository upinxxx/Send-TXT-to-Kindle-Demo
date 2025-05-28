# Send TXT to Kindle Demo

This demo illustrates how users can upload a TXT file, have it converted to EPUB, and send it to their Kindle device via Amazon SES. It is intended solely for AWS SES Production Access review.

## Demo Structure

- **User workflow**

  1. User uploads a `.txt` manuscript.
  2. System converts the text to an EPUB file in memory.
  3. System sends exactly one EPUB attachment via SES to the user’s Kindle address.

- **Kindle whitelist requirement**  
  Users must add **`noreply@syosetu2epub.online`** to their “Approved Personal Document E-mail List” in their Amazon account settings before sending.

- **Transactional email only**
  - One file = one email
  - No marketing content or bulk sends

https://demo.syosetu2epub.online/
