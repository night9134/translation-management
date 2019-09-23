W3C는 그 이전까지 track된 W3C Spec들과 문서들의 Volunteer 번역이 있는 번역 DB를 유지보수 하는 것을 중단한다고 [발표](http://lists.w3.org/Archives/Public/w3c-translators/2017JanMar/0000.html)했다. 

이 repository는 Volunteer 번역 관리하기 위해 새로운 접근의 개발과 deployment를 위한 Tracker로서, volunteer 번역들과 그들의 번역을 촉진시키고 W3C 기술 향상을 하기 위한 강력한 지원을 제공한다. 
 
The main orientations of the new system would be:
* making it based on github - all W3C groups develop their specifications on github nowadays, and anchoring the translation work on the same platform provides opportunities for better alignment with the specification process, as well as a natural platform for collaborating on the development and maintenance of translations
* setting up some minimal level of quality reviews on translations - the volunteer translation program has in the past been abused by spammers, which among thing meant that the value of the otherwise excellent work done by most of our translators would be diluted by some less reliable work
* having W3C automatically publish a copy of the translated documents under its own control - this is to ensure that the useful work done by translators remain available to the community even after the said translators are no longer interested or in a position to keep it available on their own site


In more details, the new workflow would be:
* a translator signals their intent to translate by raising an issue in
a well-defined github repository (see [#1](https://github.com/w3c/translation-management/issues/1))
* as an opt-in, other translators of that language get notified of that intent (and possibly, signal their intent to help with the effort) (see [#1](https://github.com/w3c/translation-management/issues/1))
* once the translator(s) finishes the translation, they bring the translated document via a pull request to a well-defined repo
* a team of identified reviewers for that language get notified and are expected to make a high-level review of the document to ensure a minimum level of quality (e.g. avoid spam, low-quality automated translation); optionally, these reviewers can provide more detailed feedback as non-blocking requests for enhancements (see [#2](https://github.com/w3c/translation-management/issues/2))
* via a github automated check, a number of automatic validation are run on the translation (presence of a disclaimer, HTML validity, ...) (see [#2](https://github.com/w3c/translation-management/issues/2))
* once these automated checks pass and at least one reviewer validates the translation, the translation is automatically published by W3C and linked from relevant W3C pages (see [#4](https://github.com/w3c/translation-management/issues/4))
* the same repository where the translation document was brought via a pull request is used to maintain the translations as changes in the original document or mistakes in the translation get reported (see [#3](https://github.com/w3c/translation-management/issues/3))


========================================================================================================================================

In January 2017, W3C [announced](http://lists.w3.org/Archives/Public/w3c-translators/2017JanMar/0000.html) it had to stop the maintenance our translation database where volunteer translations of W3C specifications and documents had been tracked.

This repository serves as a tracker for the development and deployment of a new approach to the management of volunteer translations, which would offer stronger
support to volunteer translators and an improved ability to W3C to promote their translations.

The main orientations of the new system would be:
* making it based on github - all W3C groups develop their specifications on github nowadays, and anchoring the translation work on the same platform provides opportunities for better alignment with the specification process, as well as a natural platform for collaborating on the development and maintenance of translations
* setting up some minimal level of quality reviews on translations - the volunteer translation program has in the past been abused by spammers, which among thing meant that the value of the otherwise excellent work done by most of our translators would be diluted by some less reliable work
* having W3C automatically publish a copy of the translated documents under its own control - this is to ensure that the useful work done by translators remain available to the community even after the said translators are no longer interested or in a position to keep it available on their own site


In more details, the new workflow would be:
* a translator signals their intent to translate by raising an issue in
a well-defined github repository (see [#1](https://github.com/w3c/translation-management/issues/1))
* as an opt-in, other translators of that language get notified of that intent (and possibly, signal their intent to help with the effort) (see [#1](https://github.com/w3c/translation-management/issues/1))
* once the translator(s) finishes the translation, they bring the translated document via a pull request to a well-defined repo
* a team of identified reviewers for that language get notified and are expected to make a high-level review of the document to ensure a minimum level of quality (e.g. avoid spam, low-quality automated translation); optionally, these reviewers can provide more detailed feedback as non-blocking requests for enhancements (see [#2](https://github.com/w3c/translation-management/issues/2))
* via a github automated check, a number of automatic validation are run on the translation (presence of a disclaimer, HTML validity, ...) (see [#2](https://github.com/w3c/translation-management/issues/2))
* once these automated checks pass and at least one reviewer validates the translation, the translation is automatically published by W3C and linked from relevant W3C pages (see [#4](https://github.com/w3c/translation-management/issues/4))
* the same repository where the translation document was brought via a pull request is used to maintain the translations as changes in the original document or mistakes in the translation get reported (see [#3](https://github.com/w3c/translation-management/issues/3))
