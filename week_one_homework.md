# Week One

* Create a public repository on Github called ruby-circus
* Add stonean as a collaborator
* Create a State class in a file called state.rb
* The object should provide the following functionality:

Open up irb

    astone$ irb

Require your state.rb

    irb(main):001:0> require './state.rb'

Instantiate a state object

    irb(main):001:0> state = State.new

Call a method that will give me the state name by the abbreviation

    irb(main):001:0> state.name('Ga')
    => "Georgia"

Call a method that will give me the state abbreviation by the name

    irb(main):001:0> state.abbreviation('Georgia')
    => "Ga"

Call a method that will give me an array of all the state names in alphabetical order

    irb(main):001:0> state.all
    => ["Alabama", "Alaska", <and so on>]

Call a method that will give me an array of all the state abbreviations in alphabetical order

    irb(main):001:0> state.all_abbreviations
    => ["AL", "AK", <and so on>]

