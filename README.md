PayPal Subscriptions Test

- Included 'paypal.standard.ipn' in Installed apps
- Created a 'magazines' app and included it in Installed apps
- Created Magazine and Purchase classes
- Created a custom template tag in products/templatetags/magazine_extras.py
- Created a magazines.html template, a view and added the URL to render the subscriptions
- Used login_required decorator from accounts views to ensure that subscriptions come up only after the user has logged in
