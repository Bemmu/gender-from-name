gender-from-name
================

    import gender
    print gender.gender['LEIA'] # prints 'female'
    print gender.gender['LUKE'] # prints 'male'

Just a simple dict derived from census bureau data http://www.census.gov/genealogy/names/names_files.html
I fully recognize there is no right answer as to which gender a name is (or even what "gender" means), but
this can still be useful for stats purposes. For ambiguous names gender is the one which had more people
that census thinks belong to that gender.


