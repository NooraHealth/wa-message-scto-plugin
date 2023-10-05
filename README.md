## Required parameters

| Key                   | Value                                                                                                                  |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `phoneNumber`         | This is the phone number that will receive the WhatsApp template message.                                              |
| `apiUrl`              | This is the URL of the API endpoint that will be invoked to send the WhatsApp message.                                 |
| `apiToken`            | This is the authentication token for the Turn Account associated with the WhatsApp Line where the template is located. |
| `whatsappNamespaceId` | This is the WhatsApp Namespace ID where the template message is located.                                               |
| `whatsappTemplateId`  | This is the WhatsApp Template Message ID, which will be used for sending a message to the user on WhatsApp.            |
| `language`            | This language code specifies the language in which the template message should be sent.                                |

### Turn API and other credentials 
To access all Turn API credentials, follow these steps:

1. Navigate to the Settings page.
2. Click on the 'API & Webhooks' tab.
3. Scroll down to the 'Authentication Tokens for X Whatsapp Line' section.
4. Locate and click the 'Create a Token' button.
5. Set the name for the token as 'SCTO WA Nudge Plugin.'
6. Ensure you set an expiry date well into the future to prevent it from expiring during the SurveyCTO survey's active period.
7. The value you'll obtain here will be used for `apiToken` field.
