# Terms
* __Marketing__: The entire site before you login to the application
* __Application__: Interface for managing your resources/objects

# Roadmap
1. Will need CMS API for all content. This will be a priority for any copy so tweaks can be made for marketing and application. All partners need the ability to edit all content on the site/app
1. No need for persistent DB yet
     * Once one is needed, [Firebase Free Tier](https://firebase.google.com/docs/web/setup) for immediate needs
     * We'll also want to dockerify any other backend frameworks we might need - [Laravel instance](https://github.com/nick-and-dons-healthcare/laravel-docker)
1. All of the application should be behind [Oath](https://developers.google.com/identity/protocols/OAuth2UserAgent#enable-apis). This allows us not to rely on a database for user models and we can limit permissions to a few email address (partners for now)
1. The application needs 1:1 parity between a react-native application and a progressive-web app.
