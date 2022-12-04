# Privacy Policy

## Data We Collect
All Data we collect is public data that can be accessed by any user on Discord. We collect:
- MessageID
- RoleID
- GuildID
- UserID
- Message Content

## Secure?
This data (**excluding the message content**) is practically worthless to anyone who gets hold of it. An example is listed below:
```
{
  "Guild": "769047889824841740",
  "__v": 0
}
``` 
Example taken from the `antilink` database.

*The full data document is NOT shown in this example! Only the Discord-related data we store, all MongoDB-related information is EXCLUDED from this example.*

Now... onto the *Message Content* issue

1 ~ We collect the contents of your message for the automoderation system. We **Do NOT store the contents of your message in any database!**

2 ~ The chatbot system also collects your message content, The contents of your message **ARE** shared with a 3rd party service, namely [Brainshop](https://brainshop.ai/). You can read more about how they manage your data in their [Terms Of Use](https://brainshop.ai/terms)

## Delete my data!
Most data collected by Ice can be deleted by using the commands present in Ice


**An announcement will be sent in the Ice support server [ Run /support ] when any important change is made to the privacy policy
