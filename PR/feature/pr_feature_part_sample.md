### Feature - `<feature_name>`
- For more information, please take a look at [this documentation page]();
- At this moment in time, we have added support for payments by Paypal and Google Pay. We are now missing Apple pay and Klarna.

### `#1234 - Add support for payments with Klarna`
- Briefly let reviewers know what this feature/PR aims at doing; 
- Mention any particular specifities that might raise eyebrows, and were decided during feature planning;

### What does this PR do?
- Create `IPaymentProvider` implementation for Klarna - **Special attention** at `KlarnaPaymentProvider#pay()`;
- Add icons for Klarna;
- Unit tests `KlarnaPaymentProvider.js`
- closes #1234

### Showcase
`<video showcase of a payment being executed through the provider/>`

Thank you for taking the time to review. Please let me know if you disagree or see any issues with the implementation of `KlarnaPaymentProvider#pay()`