# TODO

- Only have `options` method return values that map to search methods; it doesn't track any `attr_accessor` you may have. This guarantees consistent contents.
- Run rcov and mutant
- Make nice Github page
- Test with ActiveRecord 4
- Add more complex example searches to show where Searchlight shines. Eg: for a given disease, find people who've traveled in a given time period and visited countries that had an outbreak of that disease during their visit.
