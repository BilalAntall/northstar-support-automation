# Demo: return-policy support email

This example is transcribed from the supplied Gmail screenshot. The customer name and order identifier have been generalized, and the email address and profile image have been omitted.

## Customer email

> Hi,
>
> I received my order 10 days ago and haven't opened the item yet.
> Can I still return it?
>
> Order number: #DEMO-1824
>
> Thanks,
> Customer

## Draft response

> Hi Customer,
>
> Thank you for reaching out regarding order #DEMO-1824.
>
> Under our return policy, customers may request a return within 14 calendar days of receiving an item. Since you received your order 10 days ago, it is within the standard return window.
>
> For a change-of-mind return, the item must be unused, unopened, and in its original packaging. Please note that original shipping charges are typically non-refundable for these returns, and a refund can only be processed after the item has been received and reviewed by our team.
>
> If you would like to proceed with this return, please let us know so we can assist you with the next steps.
>
> Best regards,

## How the workflow relates to this example

The main workflow is designed to read and normalize the email, check for an existing case, classify the request, retrieve relevant policy context, draft a response, and record the case.

The screenshot directly demonstrates the customer question and the resulting Gmail draft. It does not expose execution traces, retrieved document contents, or the Google Sheets row, so those intermediate results are not independently verified by this example.

The draft answers the timing question, includes return conditions, and offers a next step. Its policy wording belongs to this project example; consult the actual knowledge base for the complete policy.

[Back to the project README](../README.md)
