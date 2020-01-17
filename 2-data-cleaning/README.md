# Data Cleaning

Now that we have obtained all the data that we need, we need to clean it. We need to remove all the special characters and non-numeric characters present in the data.

We will clean the following fields:

- `height` - remove single and double quotes, and convert to inches.
- `weight` - remove the text `lbs` at the end.
- `value`, `wage` and `release_clause` - remove the currency symbol at the beginning and remove `K`/`M` suffix from the end.