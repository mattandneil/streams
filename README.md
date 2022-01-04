<a style="float: right;" href="https://githubsfdeploy.herokuapp.com?owner=mattandneil&amp;repo=streams&amp;ref=master">
    <img alt="Deploy to Salesforce" src="https://raw.githubusercontent.com/mattandneil/streams/master/README1.png" width="150" />
</a>

# Streams

Durable event pipelines that give your code the ability to recover from any error.

<br/>

## Simplest Possible Thing

1. From the **Streams** app, go to the **Services** tab.
2. Click the  **Log** service and view its detail page.
3. Click **Enqueue** then check your email.

See the log email? Here's what happened:

First your event was stored in a record, then the Log service processed it in a try-catch block with a savepoint.

Although the service just sends an email, the key takeaway is this: everything
<br/>is processed safely in a durable asynchronous context, without writing code.

![event](https://raw.githubusercontent.com/mattandneil/streams/master/README2.png)

