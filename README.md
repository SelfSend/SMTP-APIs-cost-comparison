# SMTP-APIs-cost-comparison
A regularly updated comparison table of pricing plans from all email SMTP API providers.

| **Email SMTP API Provider** | **Website**                                                   | **100K emails** | **500K emails** | **1M emails** | Tracks Delivery | Validates Addresses Before Sending |  E2E Encryption Support 🔒🛡️  |
|-----------------------------|---------------------------------------------------------------|-----------------|-----------------|---------------|-----------------|------------------------------------|-------------------------|
| SelfSend v2 (On-Premises or Hybrid)   | [github.com/SelfSend](https://github.com/SelfSend)            |  FREE*          |  FREE*          |  FREE*        | ✅ | ✅ Unlimited real-time validations (Syntax, DNS/MX, Disposable, Role-based, Spam Trap, etc) | ✅ |
| SelfSend v1 (On top of AWS-SES) | [github.com/SelfSend](https://github.com/SelfSend)        |  $10            |  $50            |  $100         | ✅ | ✅ Unlimited real-time validations (Syntax, DNS/MX, Disposable, Role-based, Spam Trap, etc) | ✅ |
| AWS SES                     | [aws.amazon.com/ses](https://aws.amazon.com/ses/)             |  $10            |  $50            |  $100         | ❌ | ❌ | ❌ |
| MessageBird (SparkPost)     | [messagebird.com](https://www.messagebird.com/)               |  $30            |  $290           |  $525         | ✅ | 🟠 Only Spam Trap Monitoring | ❌ |
| Mailtrap                    | [mailtrap.io](https://mailtrap.io/email-api/)                 |  $30*           |  $300           |  $650*        | ✅ | ❌ | ❌ |
| Twilio SendGrid             | [sendgrid.com](https://sendgrid.com/)                         |  $35*           |  $319*          |  $748         | ✅ | 🟠 Up to 2.5K validations/month (If sending +700K emails/month) | ❌ |
| SMTPServer                  | [smtpserver.com](https://smtpserver.com/api-integration)      |  $39*           |  $114           |  $185         | ✅ | 🟠 Blacklists and DNS only | ❌ |
| SendPulse                   | [sendpulse.com](https://sendpulse.com)                        |  $63            |  $234           |  $460         | ✅ | ❌ | ❌ |
| Mailgun                     | [mailgun.com](https://www.mailgun.com/)                       |  $75            |  $400           |  $700         | ✅ | ❌ | ❌ |
| SMTP.com                    | [smtp.com](https://www.smtp.com/email-api/)                   |  $80            |  $300           |  $500         | ✅ | ❌ | ❌ |
| MailChimp                   | [sendpulse.com](https://sendpulse.com)                        |  $80            |  $378           |  $656         | ✅ | ❌ | ❌ |
| Mailjet                     | [mailjet.com](https://www.mailjet.com/products/email-api/)    |  $105           |  $470           | Upon request / Enterprise | ✅ | 🟠 Up to 2K validations/month (If sending +100K emails/month) | ❌ |
| Postmark                    | [postmarkapp.com](https://postmarkapp.com/)                   |  $110           |  $475           |  $700         | ✅ | ❌ | ❌ |

### Notes:
- **FREE*** (SelfSend v2) when self-hosted, only operational costs would apply, such as hosting, etc.
- Prices with **\*** have specific conditions (e.g., volume discounts, tiered pricing).
- **Mailjet** and **Postmark** are the most expensive for 100K emails.

#### Last Updated on Apr 15, 2025
