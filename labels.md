## Global Label List
This list of labels should be applied to each repository. Some repositories may have custom labels that do not suit the 'global' need, and are acceptable.

To request a change to an existing label, add a new label, or remove a label from the global list, [submit a new issue](https://github.com/sandhillsdevelopment/repo-template/issues/new/choose).

### Label Colors
Each label grouping has a specific 'hue' assigned to it. At most we should be using 2 hues per group (with exception being the `priority` prefix which has 3 hues). The more saturated color (darker the color) means an action is needed. For instance the `type-request` ![#117864](https://placehold.it/15/117864/000000?text=+) is darker than the other `types` ![#76D7C4](https://placehold.it/15/76D7C4/000000?text=+) as it denotes that a lead needs to assess the request, and assign the appropriate `type` label. Same for the `workflow` list. `workflow-has-pr` ![#F5CBA7](https://placehold.it/15/F5CBA7/000000?text=+) is not an 'actionable' status, where as `workflow-needs-testing` ![#AF601A](https://placehold.it/15/AF601A/000000?text=+) is, so `workflow-needs-testing` has a darker hue for the grouping.

| Label | Description | Color
| --- | --- | --- 
| type-bug | Denotes a bug or defect in the project. | ![#76D7C4](https://placehold.it/15/76D7C4/000000?text=+) `#76D7C4` |
| type-request | Used to identify requests for features or improvements that still need to be 'blessed' by the project lead(s) | ![#117864](https://placehold.it/15/117864/000000?text=+) `#117864` |
| type-duplicate | When a `type-request` or `type-bug` is the same as one already submitted that has been blessed or confirmed. | ![#76D7C4](https://placehold.it/15/76D7C4/000000?text=+) `#76D7C4` |
| type-feature | Functionality that does not exist. Should be used for new concepts only. | ![#76D7C4](https://placehold.it/15/76D7C4/000000?text=+) `#76D7C4` |
| type-improvement | Simliar to `type-feature` however denotes improving an existing feature. | ![#76D7C4](https://placehold.it/15/76D7C4/000000?text=+) `#76D7C4` |
| type-regression | Similar to `type-bug` however defines an issue as something that previously worked, but is no longer working. | ![#76D7C4](https://placehold.it/15/76D7C4/000000?text=+) `#76D7C4` |
| component-admin | Anything related to the adminsitrative control panels. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-api | Issues affecting (WP)REST APIs | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-cli | Integrations with command line interfaces like shell scripts or WP CLI | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-database | Custom database tables, schemas, data structures stored in the database. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-emails | The configuration, genrating, and sending of emails. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-meta | When data storage must use the meta concept. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-settings | Affecting the rendering, saving, retrieving, and logic around our settings. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-shortcodes | Related to the WordPress shortcode concept. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-templates | Any bundled templates for the front-end view. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-theme | Promoting and allowing theming platforms to integrate with our product. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-tools | Functionality geared towards tooling, import/export, and management of data.  | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-upgrades | Used when upgrading a dataset is required. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| component-widgets | Anything related to the widgitization of our platforms. | ![#7FB3D5](https://placehold.it/15/7FB3D5/000000?text=+) `#7FB3D5` |
| scope-accessibility | Changes related to the accessibility of our projects. | ![#C39BD3](https://placehold.it/15/C39BD3/000000?text=+) `#C39BD3` |
| scope-build | Tools for generating our builds, including webpack, grunt, CI/CD, etc. | ![#C39BD3](https://placehold.it/15/C39BD3/000000?text=+) `#C39BD3` |
| scope-dependency | Items depended upon via composer or npm. | ![#C39BD3](https://placehold.it/15/C39BD3/000000?text=+) `#C39BD3` |
| scope-internationalization | Translations and supporting currencies. | ![#C39BD3](https://placehold.it/15/C39BD3/000000?text=+) `#C39BD3` |
| scope-performance | Improving the performance of our products. Could be front-end, back-end, or render efficiency in the browser. | ![#C39BD3](https://placehold.it/15/C39BD3/000000?text=+) `#C39BD3` |
| scope-ui | Items reltaed to improving or fixing issues with the user interface. | ![#C39BD3](https://placehold.it/15/C39BD3/000000?text=+) `#C39BD3` |
| scope-unit-tests | Adding, fixing, improving our unit tests. | ![#C39BD3](https://placehold.it/15/C39BD3/000000?text=+) `#C39BD3` |
| scope-back-compat | Related to supporting backwards compatibility. Slightly related to `type-regression` but not always paired. | ![#C39BD3](https://placehold.it/15/C39BD3/000000?text=+) `#C39BD3` |
| workflow-blocker | This task blocks another task. Please cross link via comments in GitHub. | ![#AF601A](https://placehold.it/15/AF601A/000000?text=+) `#AF601A` |
| workflow-docs | Needs customer facing or internal documentation to be added or updated. | ![#F5CBA7](https://placehold.it/15/F5CBA7/000000?text=+) `#F5CBA7` |
| workflow-has-pr | Has a pull-request assocaited with it. | ![#F5CBA7](https://placehold.it/15/F5CBA7/000000?text=+) `#F5CBA7` |
| workflow-needs-lead-feedback | A product and/or development lead needs to give feedback. | ![#AF601A](https://placehold.it/15/AF601A/000000?text=+) `#AF601A` |
| workflow-needs-refresh | For pull-requests: This pull-request is out of date and needs to be refreshed. | ![#AF601A](https://placehold.it/15/AF601A/000000?text=+) `#AF601A` |
| workflow-needs-replication | Usually associated with the `type-bug` label, and identifies something that needs another person to replcate in order to move forward. | ![#AF601A](https://placehold.it/15/AF601A/000000?text=+) `#AF601A` |
| workflow-needs-reporter-feedback | A developer or lead needs feedback from the original reporter of the issue in order to move forward. | ![#AF601A](https://placehold.it/15/AF601A/000000?text=+) `#AF601A` |
| workflow-needs-testing | An issue has code committed against it that requires testing to be done to confirm it either fixes a `type-bug` or satisfies the requirements. | ![#AF601A](https://placehold.it/15/AF601A/000000?text=+) `#AF601A` |
| workflow-needs-unit-tests | Code has been committed that needs to have unit tests built to verify that it meets the back-end requirements. | ![#AF601A](https://placehold.it/15/AF601A/000000?text=+) `#AF601A` |
| workflow-no-action | When an issue has no action to be taken, it is closed with this label attached, and all other labels removed. | ![#F5CBA7](https://placehold.it/15/F5CBA7/000000?text=+) `#F5CBA7` |
| workflow-has-ticket | This label is used by our support staff to identify when there is a support ticket that needs follow-up. | ![#F5CBA7](https://placehold.it/15/F5CBA7/000000?text=+) `#F5CBA7` |
| integration-extension | Used to identify an internal integration within the project scope. Integrating with our other products should be their own label and will vary by product. | ![#F9E79F](https://placehold.it/15/F9E79F/000000?text=+) `#F9E79F` |
| integration-other | Used to idendify 3rd party integrations, services, or applications. | ![#F9E79F](https://placehold.it/15/F9E79F/000000?text=+) `#F9E79F` |
| priority-high | Not to be confused with 'urgency'. Priority is used to help when planning and identifying items that need to be included in releaes. | ![#CB4335](https://placehold.it/15/CB4335/000000?text=+) `#CB4335` |
| priority-normal | This is our normal priority, and should be used when doing final scoping of a release to help idenfiy the need to include in the release cycle. | ![#F1948A](https://placehold.it/15/F1948A/000000?text=+) `#F1948A` |
| priority-low | A task that does not need to be included immediately, but should not be skipped over. | ![#FADBD8](https://placehold.it/15/FADBD8/000000?text=+) `#FADBD8` |

## Gateway Labels
| Label | Description | Color |
| --- | --- | --- |
| gateway-manual | This includes our manual and 'test' gateway | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
| gateway-stripe | Integrations with Stripe.com ([Docs](https://stripe.com/docs/api)) | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
| gateway-paypal-standard | Integrations with the PayPal Standard gateway ([Docs](https://developer.paypal.com/docs/classic/products/mobile-paypal-payments-standard/)) | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
| gateway-paypal-express | Integrations with PayPal Express Checkout ([Docs](https://developer.paypal.com/docs/classic/express-checkout/)) | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
| gateway-paypal-pro | Integrations with PayPal Website Payments Pro ([Docs](https://developer.paypal.com/docs/classic/paypal-payments-pro/integration-guide/)) | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
| gateway-braintree | Integrations with Braintree ([Docs](https://developers.braintreepayments.com)) | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
| gateway-2checkout | Integrations with 2Checokut (off-site) ([Docs](https://knowledgecenter.2checkout.com/API-Integration/Start-using-the-2Checkout-API)) | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
| gateway-2checkout-onsite | Integrations with 2Checkout On-Site ([Docs](https://knowledgecenter.2checkout.com/API-Integration/Start-using-the-2Checkout-API)) | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
| gateway-amazon | Integrations with the Amazon Pay gateway ([Docs](https://developer.amazon.com/docs/amazon-pay/intro.html)) | ![#D5D8DC](https://placehold.it/15/D5D8DC/000000?text=+) `#D5D8DC` |
