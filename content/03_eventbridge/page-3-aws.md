---
title: "Setup AWS Event Bus"
chapter: true
weight: 3
---

# Setup AWS Event Bus

In the AWS Console, select “Services” -> Amazon Event Bridge”.

This will display the main Amazon Event Bridge screen.

On the left hand side, click on “Partner event sources” to finish our event bridge integration.

![](/images/ebaws_1.png)

Under ”Partner Event Sources” we will see our open request for integration that came from our PagerDuty account.

In order to activate it, we will click on ”Associate with event bus” button.

![](/images/ebaws_2.png)

In the ”Associate with event bus” page we can verify the name and origin of the request and optionally connect this to other accounts or organizations.

To finish the setup we click “Associate”

![](/images/ebaws_3.png)

Back in our “Partner event sources” page, we will see that the status of event bus is now ”Active”

We have completed the Amazon Event Bridge setup.
Next, we create rules that we can trigger from our PagerDuty Account.

![](/images/ebaws_4.png)



{{% notice warning %}}
<p style='text-align: left;'>
The examples and sample code provided in this workshop are intended to be consumed as instructional content. These will help you understand how various AWS services can be configured to work with PagerDuty.
</p>
{{% /notice %}}