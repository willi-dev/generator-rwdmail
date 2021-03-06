# Responsive email template generator for Yeoman

Quickly spit out a template for platforms such as Campaign Monitor, Mailchimp, and Mandrill.


## Credit

[MailChimp](http://mailchimp.com/) for their [email blueprints](https://github.com/mailchimp/email-blueprints)

## Setup

Once you're up and running with [Yeoman](http://yeoman.io/), install the generator:

    npm install -g generator-rwdmail

Then create a new directory a `cd` into it:

    mkdir my-email && cd $_

And call your Yeoman:

	yo rwdmail

## Usage

Run `grunt` from your project directory to run a local server and develop in real-time.

When you're ready for production, run `grunt build` to compile the template into __dist__.

If you're building specifically for [Campaign Monitor](http://www.campaignmonitor.com/), run `grunt cm`, then upload __index.html__ and __assets.zip__.

If you're building specifically for [Mailchimp](http://mailchimp.com/), run `grunt mc`, then upload __index.html__ and __assets.zip__.

If you're building specifically for [Mandrill](http://mandrillapp.com), run `grunt mandrill`, then upload __index.html__.

## License

[MIT](http://opensource.org/licenses/MIT)
