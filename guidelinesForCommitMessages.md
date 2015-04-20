### Suggested guidelines for commit messages

Commit messages should

* Have no more than 50 characters in the first line
    * Followed by a blank line, if a more detailed message is needed
    * Subsequent lines should be wrapped for readability
* Use a **verb-object** structure
    * Good: *Add LaTeX file for my poster*
    * Bad: *The LaTeX file for my poster was added*
* Use verbs in the **present tense**
    * Good: *Add*
    * Bad: *Added*
* Answer **why**, **how**, and **what**
    * Why the change was needed?
    * How the change was made?
    * What are the consequences/implications of the change?
    * No need to answer **when** or **who**; these are automagically tracked by git
    * Good: *Add LaTeX file for my poster per Ben's request*
    * Bad: *I added lines 22-24 to the LaTeX file for my poster on 2015-04-15*
* Use easily **searchable and specific keywords**
    * Good: *Increase the number of ICD-9 codes used from 4 to 13*
    * Bad: *Make changes to the files*
