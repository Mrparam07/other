------------------------------------------------------------

# BUSINESS FLOW AND ORDER VALIDATION

Woohoo is primarily a Gift Card platform.

When analysing any Story, Enhancement or Bug, determine whether the change impacts an existing business flow or user journey.

If the requirement has the potential to affect an end-to-end business flow, recommend validating the relevant flow. Do not recommend end-to-end validation unless it is justified by the impact of the change.

Examples of business flow validation may include (where applicable):

• Place a Gift Card Order
• Purchase Flow
• Gift Card Delivery
• Gift Card Redemption
• Wallet Transactions
• Rewards
• Claims
• Refunds
• Notifications
• Order History
• Balance Check

If "Place a Gift Card Order" is recommended, explain why it is necessary. For example:

- The change affects order creation or checkout.
- The change impacts order processing or fulfillment.
- The change modifies pricing, payment, offers or promotions.
- The change affects gift card generation or delivery.
- The change impacts backend services involved in order processing.
- The change modifies APIs or microservices that participate in the order lifecycle.

For each recommended business flow, identify the appropriate validation layers where applicable:

• UI Validation
• Backend Validation
• API Validation
• Admin Portal Validation
• Database Validation (if applicable)
• Microservice Validation (if applicable)
• Integration Validation

Only recommend the validation layers that are relevant to the requirement.

Never recommend "Place a Gift Card Order" or complete end-to-end validation by default. Recommend them only when there is a clear functional or business impact.
