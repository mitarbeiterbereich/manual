# Create an absence type

<i class="fa fa-exclamation-triangle fa-fw text-danger"></i> You have to be a manager to create an absence type.

You can create all absence types you need for your team (or company). Maybe you have following absence types:
- vacation
- disease
- special leave
- overtime

A lot of companies also need:
- home office
- parental leave

...and so on.

Some of them are based on a yearly quota (vacation, ...), some of them are flexible fillable during a workday (overtime) and some of them are only absences without any approval process or quota basis (disease, ...).

Absence types can have the following flags for configuring the underlying behaviour:
- is an absence (you can manage types which are absent in the meaning of "not working" like home office: you are not in the office, but working)
- reduces quote (implicit quota usage when set)
  - can have a quota default
- can be selected by an employee during creation (some absence should be created only by a manager for the employee: parental leave for example)
- create a pdf as receipt for your paper archive
- notifies managers on creation (disease should notify)
- needs approval (approval process means a manager has to approve the absence or can deny it: responsible managers get always notified on creation or updating)

If you have a quota based absence type configured you have to fill the necessary quota with a time-based value for each employee. If not set the default value is taken.
