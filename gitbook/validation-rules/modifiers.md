### Modifiers

Additional rules for data modification. They do not return errors just skips values that are not appropriate.

#### trim {#trim}

Removes leading and trailing spaces. Skips object references.

Example:

```text
{email: 'trim'}
```

#### to\_lc {#to-lc}

Converts string to lower case. Skips object references.

Example:

```text
{email: 'to_lc'}
```

#### to\_uc {#to-uc}

Converts string to upper case. Skips object references.

Example:

```text
{currency_code: 'to_uc'}
```

#### remove {#remove}

Removes characters from string

Example:

```text
{ text: { remove: '0123456789' } }  // Remove all numbers from text
```

#### leave\_only {#leave-only}

Removes characters from string

Example:

```text
{ text: { leave_only: '0123456789' } }  // Leaves only numbers in text
```

#### default {#default}

Set value if is not present.

Example:

```text
{ age: { default: 18 } }  // Sets age to 18 if not passed
```

## 



