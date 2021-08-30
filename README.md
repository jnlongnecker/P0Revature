# Revature Champs Project
The ContactExisting trigger does nothing but append useless text to a duplicate contact. Not only is this allowing the duplicate (which is assumed to be unwanted), but it also would cause it to longer match any matching rules, meaning now you have a duplicate that isn't detectable by a declarative solution but would have been if this trigger hadn't fired. In essence, this trigger is actually more harmful than beneficial. The EmailExistence trigger is not only useless in the exact same way, but is not functionality unique, which was a requirement of the project. In case that wasn't enough, the InsertDescription functionality quite literally does nothing; it makes no impact on the data whatsoever and simply makes the default SOOE less efficient because it has to run this trigger.

Finally, not only is the code not useful, but the tests don't even test that they do the functionality that is there. In fact, most of the tests don't pass, and there is 15% code coverage. The only thing that shows any understanding of the material was by following trigger best practices.
