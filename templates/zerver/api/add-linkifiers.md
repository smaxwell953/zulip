# Create linkifiers

{generate_api_description(/realm/filters:post)}

## Usage examples

{start_tabs}
{tab|python}

{generate_code_example(python)|/realm/filters:post|example}

{tab|curl}

{generate_code_example(curl)|/realm/filters:post|example}

{end_tabs}

## Arguments

{generate_api_arguments_table|zulip.yaml|/realm/filters:post}

## Response

#### Return values

* `id`: The numeric ID assigned to this filter.

#### Example response

A typical successful JSON response may look like:

{generate_code_example|/realm/filters:post|fixture(200)}
