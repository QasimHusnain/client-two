---
paths:
  - "campaigns/**/emails/*.md"
---

# Rules for email files

These rules apply to every email file in any campaign. Each email file must follow them all.

## Top of the file

- The first line is `Subject: ...`, and the subject is 50 characters or fewer.
- The second line is `Preview: ...`, and the preview text is 90 characters or fewer.

## Greeting

- Greet the reader with `{{first_name}}`, for example "Hi {{first_name}},".

## The one main link

- Have exactly one main link, written exactly like this:
  [See the spring bakes](https://riseandcrumb.example/spring)
- Put "Call us on 07700900456" beside it as plain text. The phone number is not a second link.

## End of the email

Close in this order:

1. Our sign-off from `brand/voice.md`:

   Fresh from the oven,
   The Rise & Crumb team

2. The footer link from the "Email layout" section of `brand/voice.md`:
   - Website: https://riseandcrumb.example/

3. This two-line footer, written as plain text and not inside a code block:

   You're getting this because you've visited Rise & Crumb or joined our mailing list.
   Rise & Crumb, {{company_address}} · Unsubscribe: {{unsubscribe_url}}
