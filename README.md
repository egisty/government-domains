# Government Domains
This repository contains lists of official domain names administered by governments and government-related organizations in a machine-readable format.

## Structure

> **Note:** The information contained in this repository may differ from current information due to update delays. Please consult the respective original publisher to obtain up-to-date information.

To access a government domain record, please use the following scheme:

```
egisty/government-domains/{CountryCode}/.{tld}/data.json
```

All domain records have the following internal structure:

```json
{
    "domains": [
        {
            "Domain Name": "example.tld",
            "Domain Type": "Domain Type",
            "Agency": "Agency Type",
            "Organization": "Organization Name",
            "City": "City Name",
            "State": "State Code",
            "Security Contact Email": "name@example.tld"
        }
    ],
    "updatedOn": "dd.mm.yyyy, hh:mm:ss",
    "version": 1,
    "source": "https://www.example.org"
}
```

## What is the data?
The files that are listed in this repository contain domain information from federal agencies as well as states, territories, cities, counties, and native tribes.This should make it easier for a large number of people to obtain official domain information from a verified source without having to carry out extensive research beforehand.

For the direct use of the data by developers, the lists, have been converted into JSON format, since parsers are available for this purpose in all common programming languages.

## Report incorrect or missing data
If you have found wrong or missing domain data in our domain records, you can get started very easily.

#### Please choose if you want to report incorrect or missing domain data.
- Report incorrect domain data: [Click here](https://github.com/egisty/government-domains/issues/new?assignees=&labels=&template=incorrect-domain-data-report.md&title=)
- Report missing domain data: [Click here](https://github.com/egisty/government-domains/issues/new?assignees=&labels=&template=missing-domain-data-report.md&title=)

**Note:** The more information you provide, the better we can help you. Therefore, always pay attention to a large amount of detail.

## License

Please see the [license file](https://github.com/egisty/government-domains/blob/master/LICENSE) for more information.
