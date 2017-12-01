# FBLogin Example

This is a simple example app that shows how to use the FB Login button widget.

## Running this Sample

1. Download it.
2. Set your site domain in app setting (see below)
3. Run `npm install`
4. Run `node index.js` to start server of localhost
5. Open `index.html` in your browser
6. Click the button!

### Setting Your Site Domain

To run this on your website, do the following in your FB app settings (localhost used as an example):

1. In 'Settings' > 'Basic', click '+Add Platform'
2. Click 'Website'
3. Enter `http://localhost:<port>` as the URL, where `<port>` is whatever port you're running on
4. In the 'App Domains' field, enter `localhost`
5. Click the 'Save Changes` button

## Scopes

This sample is configured to auth the following scopes:

- `manage_pages`
- `public_profile`
- `email`

See the FB docs for a [complete set of scopes](https://developers.facebook.com/docs/facebook-login/permissions).

## Behold!

<h4 align="center"><img src="https://github.com/amuramoto/FB-Sample-Apps/raw/master/FB-login/images/Screen%20Shot%202017-11-28%20at%204.34.29%20PM.png" alt="logged out" /> <img src="https://github.com/amuramoto/FB-Sample-Apps/raw/master/FB-login/images/Screen%20Shot%202017-11-28%20at%204.34.09%20PM.png" alt="logged in" /></h4>
