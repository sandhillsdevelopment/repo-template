## Global Label List
This list of labels should be applied to each repository. Some repositories may have custom labels that do not suit the 'global' need, and are acceptable.

| Label | Description | Color
| --- | --- | --- 
| type-bug | Denotes a bug or defect in the project. | ![#993333](https://placehold.it/15/993333/000000?text=+) `#993333` |
| type-request | Used to identify requests for features or imrovements that still need to be 'blessed' by the project lead(s) | ![#669999](https://placehold.it/15/669999/000000?text=+) `#669999` |
| type-duplicate | When a `type-request` or `type-bug` is the same as one already submitted that has been blessed or confirmed. | ![#333333](https://placehold.it/15/333333/000000?text=+) `#333333` |
| type-feature | Functionality that does not exist. Should be used for new concepts only. | ![#669999](https://placehold.it/15/669999/000000?text=+) `#669999` |
| type-improvement | Simliar to `type-feature` however denotes improving an existing feature. | ![#669999](https://placehold.it/15/669999/000000?text=+) `#669999` |
| type-regression | Similar to `type-bug` however defines an issue as something that previously worked, but is no longer working. | ![#993333](https://placehold.it/15/993333/000000?text=+) `#993333` |
| component-admin | Anything related to the adminsitrative control panels. | |
| component-api | Issues affecting (WP)REST APIs | |
| component-cli | Integrations with command line interfaces like shell scripts or WP CLI | |
| component-database | Custom database tables, schemas, data structures stored in the database. | |
| component-emails | The configuration, genrating, and sending of emails. | |
| component-meta | When data storage must use the meta concept. | |
| component-settings | Affecting the rendering, saving, retrieving, and logic around our settings. | |
| component-shortcodes | Related to the WordPress shortcode concept. | |
| component-templates | Any bundled templates for the front-end view. | |
| component-theme | Promoting and allowing theming platforms to integrate with our product. | |
| component-tools | Functionality geared towards tooling, import/export, and management of data.  | |
| component-upgrades | Used when upgrading a dataset is required. | |
| component-widgets | Anything related to the widgitization of our platforms. | |
| scope-accessibility | Changes related to the accessibility of our projects. | |
| scope-build | Tools for generating our builds, including webpack, grunt, CI/CD, etc. | |
| scope-dependency | Items depended upon via composer or npm. | |
| scope-internationalization | Translations and supporting currencies. | |
| scope-performance | Improving the performance of our products. Could be front-end, back-end, or render efficiency in the browser. | |
| scope-ui | Items reltaed to improving or fixing issues with the user interface. | |
| scope-unit-tests | Adding, fixing, improving our unit tests. | |
| scope-back-compat | Related to supporting backwards compatibility. Slightly related to `type-regression` but not always paired. | |
| workflow-blocker | This task blocks another task. Please cross link via comments in GitHub. | |
| workflow-docs | Needs customer facing or internal documentation to be added or updated. | |
| workflow-has-pr | Has a pull-request assocaited with it. | |
| workflow-needs-lead-feedback | A product and/or development lead needs to give feedback. | |
| workflow-needs-refresh | For pull-requests: This pull-request is out of date and needs to be refreshed. | |
| workflow-needs-replication | Usually associated with the `type-bug` label, and identifies something that needs another person to replcate in order to move forward. | |
| workflow-needs-reporter-feedback | A developer or lead needs feedback from the original reporter of the issue in order to move forward. | |
| workflow-needs-testing | An issue has code committed against it that requires testing to be done to confirm it either fixes a `type-bug` or satisfies the requirements. | |
| workflow-needs-unit-tests | Code has been committed that needs to have unit tests built to verify that it meets the back-end requirements. | |
| workflow-no-action | When an issue has no action to be taken, it is closed with this label attached, and all other labels removed. | |
| workflow-has-ticket | This label is used by our support staff to identify when there is a support ticket that needs follow-up. | |
| integration-extension | Used to identify an internal integration within the project scope. Integrating with our other products should be their own label and will vary by product. | |
| integration-other | Used to idendify 3rd party integrations, services, or applications. | |
| priority-high | Not to be confused with 'urgency'. Priority is used to help when planning and identifying items that need to be included in releaes. | |
| priority-normal | This is our normal priority, and should be used when doing final scoping of a release to help idenfiy the need to include in the release cycle. | |
| priority-low | A task that does not need to be included immediately, but should not be skipped over. | |

## Gateway Labels
| Label | Description | Color |
| --- | --- | --- |
| gateway-manual | This includes our manual and 'test' gateway | |
| gateway-stripe | Integrations with Stripe.com ([Docs](https://stripe.com/docs/api)) | |
| gateway-paypal-standard | Integrations with the PayPal Standard gateway ([Docs](https://developer.paypal.com/docs/classic/products/mobile-paypal-payments-standard/)) | |
| gateway-paypal-express | Integrations with PayPal Express Checkout ([Docs](https://developer.paypal.com/docs/classic/express-checkout/)) | |
| gateway-paypal-pro | Integrations with PayPal Website Payments Pro ([Docs](https://developer.paypal.com/docs/classic/paypal-payments-pro/integration-guide/)) | |
| gateway-braintree | Integrations with Braintree ([Docs](https://developers.braintreepayments.com)) | |
| gateway-2checkout | Integrations with 2Checokut (off-site) ([Docs](https://knowledgecenter.2checkout.com/API-Integration/Start-using-the-2Checkout-API)) | |
| gateway-2checkout-onsite | Integrations with 2Checkout On-Site ([Docs](https://knowledgecenter.2checkout.com/API-Integration/Start-using-the-2Checkout-API)) | |
| gateway-amazon | Integrations with the Amazon Pay gateway ([Docs](https://developer.amazon.com/docs/amazon-pay/intro.html)) | |