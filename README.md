Streams are durable event pipelines that give your code the ability to recover from any error.

<br/>

## Simplest Possible Thing

1. From the **Streams** app, go to the **Services** tab.
2. Click the  **Log** service and view its detail page.
3. Click **Enqueue** then check your email.

See the log email? Here's what happened:

First your event was stored in a record, then the Log service processed it in a try-catch block with a savepoint.

Although the service just sends an email, the key takeaway is this: everything
<br/>is processed safely in a durable asynchronous context, without writing code.

![event](https://raw.githubusercontent.com/mattandneil/streams/master/README.png)

While we can't provide ad-hoc support for this code, please contact us with your company<br/>name and address if you need a warranty for its use and we will assist: [www.tostring.co.uk/contact](https://www.tostring.co.uk/contact)
