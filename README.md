# Inventory of Latin lexical entities

This repository hosts a simple list of attested Latin vocabulary with unique identifiers for each.
You can see the current list in a web browser [here](invfile).

In addition to the information in this README, see the [project wiki][projectwiki].

## What's in the inventory ##

The inventory records three pieces of information:  a URN identifying the vocabulary item (lexical entity), a human-readable label, and a URN citing a passage of text where the item occurs. (If you're new to URNs, see the help on the project wiki.)




[projectwiki]: https://github.com/LinguaLatina/lexicalinventory/wiki

[ghhelppull]: https://help.github.com/articles/using-pull-requests

[invfile]: https://github.com/LinguaLatina/lexicalinventory/blob/master/inventory.csv

## How to contribute ##

You can fork a copy of this repository, edit your copy, and submit your contributions using github's regular system of pull requests.  Since the repository consists exclusively of simple structured text files, you can even do all your editing from a web browser. 

If you're new to pull requests, you might want to look at [github's help page][ghhelppull] on the topic.




### Prerequisite:  register a unique prefix for your contributions ###

Vocabulary items (or lexical entities) are identified by CITE URN.  (For a quick guide to CITE URNs, see this [page in the wiki][citeurnhelp].)  You'll need a unique string prefix to ensure that you can safely create unique values for CITE URNs you want to submit.

[citeurnhelp]: https://github.com/LinguaLatina/lexicalinventory/wiki/Help-and-tips

The file `prefixes.csv` has a list of unique prefix strings for contributors.  Add an entry for your team, and submit a pull request.  (You can edit your forked copy of the file on github directly in a web browser.)


### Step 1: edit the inventory.csv file ###


For each new vocabulary item you want to submit, add a single line in the `inventory.csv` file with three pieces of data:  the proposed URN for the new item, a human-readable label and a URN citing the text passage where a form of the word occurs.

Your URN should look like this:

    urn:cite:perseus:latlexent.PREFIXSTRINGxxxx.1

where `PREFIXSTRING` will be the unique prefix you registered in `prefixes.csv`, and `xxxx` will be replaced with one or more numeric characters (0-9).  Each entry much have a unique URN value.

For more help with URNs, see the wiki.

### Step 2: submit a pull request ###

When you have added one or more records, submit a pull request.

That's it!  You'll receive a notification from github when your action is taken on your request.

