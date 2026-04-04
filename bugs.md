# Text of launchpad bug reports

...in case launchpad is down during the session.


## 2144600: Course Reserves - Reopen Selected Action Always Grayed Out

(Administration -> Local Administration -> Course Reserves List)

The Course Reserves list's action menu has an action "Reopen Selected". This action should un-archive the selected archived courses but the action is always greyed out, even when an archived course is selected.

I thought this might be a permission issue but as far as I can tell the only permission for course reserves is MANAGE_RESERVES which my test user has.

The workaround is to go into the course and use the Unarchive Course button. This is doable but is more steps.

## 2145192: No confirmation toast when adding to record bucket from search

When adding a record to a record bucket via the Add to Bucket dropdown in search results, there is no confirmation toast when the record is added to the bucket. In 3.14, you used to get the success toast "Added record 123 to bucket 456".

You also get this error in the console: ERROR TypeError: X.map is not a function
