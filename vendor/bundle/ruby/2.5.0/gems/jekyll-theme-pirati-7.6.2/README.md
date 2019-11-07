# jekyll-theme-pirati

Theme of Czech Pirate Party.

[![Gem Version](https://badge.fury.io/rb/jekyll-theme-pirati.svg)](https://badge.fury.io/rb/jekyll-theme-pirati)

## Installation & usage

For usage see [USAGE.md](USAGE.md)

## Updating to 6.x

To upgrade to v6 which features major visual upgrade, following steps are necessary:

 - For `_people` collection, remove `fullaname` property for every document. Instead, provide `titles` property to keep academic degrees in following format:

    ```
    titles:
      before: MUDr.
      after:  Ph.D.
    ```
 - To make your contact page look OK, you will need to wrap it's  sub-heading in following fashion:

    ```
    <div class="o-section-header o-section-header--indented">
      <h1 class="t-h2-alt">Přidejte se</h1>
    </div>
    ```
## Updating to 7.x

Tag `_config.yml organization contactUid` is not used. Contacts person in bottom are popele with category `kontaktni_osoba`.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/pirati-web/jekyll-theme-pirati/. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

See [development](development.md).

## License

The theme is available as open source under the terms of the [MIT
License](https://opensource.org/licenses/MIT).

