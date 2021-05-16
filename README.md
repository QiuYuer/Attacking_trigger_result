# Attacking_trigger_result
There are two folders. One folder stores the trigger lists for both unigram and 2-gram triggers, and the other one is for the evaluation data of these corrsponding triggers.

The file name is expressed by trigger length, attack class and target class.

For the trigger list, the file name is formed by "trigger_list_(trigger length)_(source class)to(target class).tsv".

For the evaluation, the file name is formed by "trigger(trigger length)\_(source class)to(target class).tsv" if these evaluations are for triggers prepending in the claim,
and when triggers are appended at the end of claims, the file name is formed by "trigger(trigger length)_(source class)to(target class)_end.tsv"
