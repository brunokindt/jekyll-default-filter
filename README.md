# Jekyll Defaut filter
A jekyll plug-in that provides the [Liquid "default" filter](https://github.com/Shopify/liquid/blob/3-0-0-rc1/lib/liquid/standardfilters.rb). The filter is just copy and paste of the Liquid "default".

## Installation
- Copy default-filter.rb to your Jekyll `_plugins` directory

## Usage:
- e.g. `Hello {{ include.world | default:"world" }}`
