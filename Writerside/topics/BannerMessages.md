

# Banner messages

Buildbase uses banners to notify the user of:
- information about the app
- success for operations
- errors that occurred

## Information messages

### Subscription status

![Subscription Banner](TrialSubscriptionBanner.png)
When a subscription nears the end a banner will be shown on all views. The color and icon depend on the remaining time.

### Appearance of the subscription banners:
- Time remaining less than 4 days: logo clock (filled) and red colored banner
  ![Subscription Expires in less than 4 days](SubscriptionBannerRed.png)
- Time remaining less than 8 days: logo clock (non-filled) and orange colored banner
  ![Subscription Expires in less than 8 days](SubscriptionBannerOrange.png)
- Time remaining more than 14 days (only with trial subscription): logo info and blue colored banner
  ![Trial Subscription for more than 14 days remaining](SubscriptionBannerBlue.png)


### Paid subscription

When the time is near to renew the subscription a banner is shown on top of all views of the app. The [appearance](#appearance-of-the-subscription-banners) of the banner
depends on the remaining time of the current subscription.
If the subscription is expired the admin can still log in. Except for the license settings all views are blocked until the subscription is renewed.
![Subscription is expired](PaidSubscriptionBannerExpired.png)

### Trial subscription

When using a trial subscription a banner is shown on top of all views of the app. The [appearance](#appearance-of-the-subscription-banners) of the banner
depends on the remaining time of the trial period.
If the trial period has expired the admin can still log in. Except for the license settings all views are blocked until a paid subscription is made.
![Subscription is expired](TrialSubscriptionBannerExpired.png)
