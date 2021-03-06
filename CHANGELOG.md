# Change Log

## 3.0.1 - 2017-01-07

### Added
- Display styles in settings to customize MailHops bar background color, font color and font size
- Polish language locale

### Removed
- Display show options, data is now always shown for:
  - Unsubscribe link
  - Mailer
  - DKIM
  - SPF
  - DNSBL

### Fixed
- Received header id parsed as an IP address
- MailHops bar showing up on load with no message selected


## 3.0.0 - 2016-12-26

### Added
- MailHops Bar for matching styles across supported mail clients

### Removed
- Thunderbird specific styles and MailHops bar from the header
- Postbox specific styles and MailHops sidebar display

## 2.0.0 - 2016-10-10

### Added
- MailHops API v2 membership
- Filters section in preferences
- Tag and mark as junk by CountryCode
- Time Traveled, total time it took for the email to reach you

### Fixed
- Bug if multiple IPs exist in one Received header
- Check for API response HTTP status code


## 1.0.8 - 2016-5-25

### Added
- Styles Updates
- SSL Default

## 1.0.7 - 2015-11-13

### Fixed
- Check that IP address starts with digit less than 240 (IANA-RESERVED)


## 1.0.6 - 2015-11-12

### Fixed
- Missing try/catch around JSON.parse


## 1.0.3 - 2015-09-18

### Added
- Map provider in preferences

### Fixed
- Save language in preferences
- Display if only city in response


## 1.0.1 - 2015-06-10
### Added
- Context.IO sponsored message, build something awesome with their API!

### Fixed
- Removed loading indicator when no received headers found
- Secure message parsing


## 1.0.0 - 2015-05-31
### Changed
- Combined Thunderbird and Postbox code into one plugin

### Fixed
- Fix mismatch IP from Microsoft SMTP id in received header


## 0.9.0 - 2015-05-30
### Changed
- Update map style and size
- Update logo

### Added
- IPV6 support
- Language support for 'de','en','es','fr','ja','pt-BR','ru','zh-CN'
- What3Words, gets the 3 words for the geo of the sender
- Forecast.IO, gets the weather from the sender, API key needs to be added in preferences

### Fixed
- Fix mismatch IP from Microsoft SMTP id in Received header
