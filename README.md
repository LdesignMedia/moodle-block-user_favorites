## Moodle block for marking your favourite pages as bookmarks

In brief, user_favorites gives the user a method to mark pages as favourite.

Special thanks to
- For the inspiration [block_user_bookmarks](https://moodle.org/plugins/block_user_bookmarks)
- Valuable contributions to enchance the plugin: @stopfstedt, 2gjb2048, and @SashaAnastasi 
- Financing the development and continous support until M4.4 ([LTNC B.V.](https://ltnc.nl/))

* Author: Luuk Verhoeven, [ldesignmedia.nl](https://ldesignmedia.nl/)
* Author: Gemma Lesterhuis, [LTNC B.V.](https://ltnc.nl/)
* Min. required: Moodle 4.2
* Supports PHP:  7.4

![Moodle402](https://img.shields.io/badge/moodle-4.2-brightgreen.svg)
![Moodle403](https://img.shields.io/badge/moodle-4.3-brightgreen.svg)
![Moodle404](https://img.shields.io/badge/moodle-4.4-brightgreen.svg)
![Moodle500](https://img.shields.io/badge/moodle-5.0-brightgreen.svg)

![PHP74](https://img.shields.io/badge/php-7.4-teal.svg)
![PHP80](https://img.shields.io/badge/php-8.0-teal.svg)
![PHP81](https://img.shields.io/badge/php-8.1-teal.svg)

## Screens
![10 27 2018-12 40](https://github.com/Lesterhuis-Training-en-Consultancy/moodle-block-user_favorites/assets/995760/2f2c2157-dbfa-4a17-9c5b-cd77ba55070c)

## List of features
- Using external AJAX requests for saving loading and ordering user favourites.
- Using mustache templates.
- Fast and easy to work with.
- Marks current page in favorites if exists.
- Allow marking as favorite the url link with `#hash` (In case of marking multiple links for the same page, A web page reload needed before).
- Make use of external API web services as in the tracker MDL-76583.

## Installation

1. Copy this plugin to the `blocks\user_favorites` folder on the server
2. Login as administrator
3. Go to Site Administrator > Notification
4. Install the plugin


## Changelog

See [Changelog](CHANGELOG.md) file for details

## Bug and Problem support

This plugin is carefully developed and thoroughly tested, but bugs and problems can always appear.
If you discover any security related issues, please email [support@ldesignmedia.nl](mailto:support@ldesignmedia.nl) instead of using the issue tracker.

Please bear in mind that bug and problem support is not free of charge. This is with the exception of developers that report and suggest a solution by creating a pull request. 

## Feature proposal
We are aware that members of the community will have other needs and would love to see them solved by this plugin. We are always interested to read about your feature proposals or even get a pull request from you, but please understand that we handle these as feature proposals and not as feature requests that we commit to implementing.

## License

Block User Favorite code is provided freely as open source software, under version 3 of the GNU General Public License.

## Contributing

Contributions are welcome and will be fully credited. We accept contributions via Pull Requests on Github.
