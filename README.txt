Welcome to the WSO2 Enterprise Service Bus (ESB) Connectors. 

A connector allows you to interact with a third-party product's functionality and data from your ESB message flow, enabling you to connect to and interact with the APIs of services such as Twitter, Salesforce, and JIRA.
This means that if you have enabled the Twitter and Google Spreadsheet connectors in your ESB instance, your message flow could receive requests containing a user's Twitter name and password, log into the user's Twitter
account, get a list of the user's followers, and write that information to a Google spreadsheet.

Each connector provides a set of operations, which you call from your proxy services, sequences, and APIs to interact with that product. For example, the Twitter connector provides operations that call the Twitter APIs 
to get and send direct messages, retrieve IDs of friends and followers, update status, retweet other users' status, and more. If you want your configuration to send a direct message to a Twitter user, you could call the 
twitter.sendDirectMessage operation and pass in the Twitter user's ID and the direct message text.
