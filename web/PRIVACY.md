# Privacy Policy

PluginRPC does not sell, rent, or monetize your personal data.
* We only process the minimum data required by the Discord API to provide the service (such as your User ID, oauth2 token [temporarily and only for authentication, as Discord is not allowing server-side presence writing yet] and the Presence status you send us). This data is used solely to provide the service.
* Our backend may log anonymized IP addresses and anonymized API requests to prevent abuse and ensure service stability.

As such the only data we store about you is a single file which contains:
* Your account ID
* A sha256 of your latest oauth2 token (refreshed on every app launch, we store it as it might be promoted to a full token if Discord allows™ in the future). <br>
* The API key WE generate for your PluginRPC devices

This service also uses Discord and Cloudflare for interacting with the users, as such their Privacy Policies will apply.

If you'd like to use our public instance you can take a look at its changes (such as the hashed token instead of a full one) compared to the server source here:  https://git.regdev.me/RegularRabbit05/PluginRPC-Dev <br>
If you'd like to self-host the service you can do so looking at the required modules here: https://github.com/stars/RegularRabbit05/lists/pluginrpc

As the service evolves those policies might be tweaked or changed to accommodate any future features, but we will try our best to keep a privacy-first approach.

For contact information please take a look at our Terms of Service.