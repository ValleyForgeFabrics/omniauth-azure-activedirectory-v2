# Omniauth::Azure::Activedirectory::V2

## Notice
- This gem is EXACTLY the same as [RIPAGlobal's](https://github.com/RIPAGlobal/omniauth-azure-activedirectory-v2)
- For reasons I don't want to get into, I needed the gem to be called `omniauth-azure_activedirectory_v2` instead of `omniauth-azure-activedirectory-v2`.
- That is all.

[![Gem Version](https://badge.fury.io/rb/omniauth-azure-activedirectory-v2.svg)](https://badge.fury.io/rb/omniauth-azure-activedirectory-v2)
[![Build Status](https://travis-ci.org/RIPGlobal/omniauth-azure-activedirectory-v2.svg)](https://travis-ci.org/RIPGlobal/omniauth-azure-activedirectory-v2)
[![License](https://img.shields.io/github/license/RIPGlobal/omniauth-azure-activedirectory-v2.svg)](LICENSE.md)

OAuth 2 authentication with [Azure ActiveDirectory's V2 API](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-overview). Rationale:

* https://github.com/marknadig/omniauth-azure-oauth2 is no longer maintained.
* https://github.com/marknadig/omniauth-azure-oauth2/pull/29 contains important additions.

This gem combines the two and makes some changes to support the full V2 API.

The ActiveDirectory V1 auth API used OpenID Connect. If you need this, a gem from Microsoft [is available here](https://github.com/AzureAD/omniauth-azure-activedirectory), but seems to be abandoned.



## Installation

Add this line to your application's Gemfile:

```ruby
gem 'omniauth-azure-activedirectory-v2'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install omniauth-azure-activedirectory-v2



## Usage

See https://github.com/marknadig/omniauth-azure-oauth2 for background information.



## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/RIPGlobal/omniauth-azure-activedirectory-v2. This project is intended to be a safe, welcoming space for collaboration so contributors must adhere to the [code of conduct](https://github.com/RIPGlobal/omniauth-azure-activedirectory-v2/blob/master/CODE_OF_CONDUCT.md).



## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).



## Code of Conduct

Everyone interacting in this project's codebases, issue trackers, chat rooms and mailing lists must follow the [code of conduct](https://github.com/RIPGlobal/omniauth-azure-activedirectory-v2/blob/master/CODE_OF_CONDUCT.md).
