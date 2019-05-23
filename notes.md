A good data model
captures all the information the system needs
captures only the information the system needs
reflects reality
if flexible, can evolve with the system
guarantees data integrity without sacrificing performance and convenience
is driven by the way the system used the data

Entities => resources => table
Properties => Columns
Relationships => Foreign Keys

Workflow

Identify the entities
identify the properties for each entity
Identify the relations between entities

Tracks => Web, Android, IOS
Cohorts => web18 webpt2
Students => Mindy, Sean, Destiny

Queries examples

select s.name as student, c.name as cohort from students as s inner join cohorts as c on s.cohort_id = c.id