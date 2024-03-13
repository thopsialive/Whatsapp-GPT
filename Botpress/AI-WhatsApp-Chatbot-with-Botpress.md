# AI WhatsApp Chatbot with Botpress

Below are the steps you have to follow to connect Botpress with WhatsApp. We will switch back and forth between Botpress and Meta Business Platform. In the example, we will build a bot that Airbnb hosts can use to help customers with frequently asked questions.

  

**Botpress**

1. [Create a Botpress Account](https://try.botpress.com/09b4u0dn0b86)
2. Create a new bot in Botpress
3. Make sure the bot is published

  

**Meta**

1. Go to or create your [Meta Developers](https://developers.facebook.com/apps/) account
2. Create App → Other → Business → Name your app → Select WhatsApp as the integration

  

**Botpress**

1. In Botpress, go to integration and click "Browse in Hub"
2. Select WhatsApp and install to your Botpress project
3. Now you have to fill Verify Token, Access Token, and default number
    *   Verify Token: a string that you can select (e.g., 12345)
    *   Access Token: In the Meta App dashboard, to API Setup and copy your temporary Access Token (valid for 24 hours)
    *   Default Number: On the API Setup page, you can also copy the Phone number ID for your test number
4. Press save and enable integration
5. Now on the same page, copy the Webhook URL from the Botpress WhatsApp integration page

  

**Meta**

1. Go back to your Meta app, select Configuration, and edit the Callback URL
2. Paste the Webhook URL and your same Verify Token that you just came up with (e.g., Again, 12345)
3. Now click verify and save
4. Now on the same page, got to Webhook fields, Manage and Subscribe to messages
5. Now go back to API Setup and add your own WhatsApp phone number You'll get a verification code via WhatsApp.
6. Next, select your phone number, click send test message and wait for your message to appear in WhatsApp (this can take 60-120 seconds).
7. Your connection with Botpress should now be live and you can start chatting!

  

**Download the PDF**

[airbnb-faq.pdf](https://t9015213037.p.clickup-attachments.com/t9015213037/1fefd4f7-2a11-4b6c-a479-95e96006e73e/airbnb-faq.pdf)



**Tutorial Source**

[Easiest Way to Connect AI Chatbots to WhatsApp](https://www.youtube.com/watch?v=OEPte4cG3Fk)
