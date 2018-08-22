# Credible Web CG Area-2 (Corroboration-Based Strategies)

This repo is for gathering work around the “corroboration” strategy of credibility assessment, which involves looking to see what others have to say about the claims being assessed.  This is area-2 of the [credible web work](https://credweb.org).

The suggested proposals in this area are:

1. Allow professional fact-checks to be published in machine readable form so they can more easily be matched, used in automated assessments, and shown to users when appropriate. (Already being done using claimreview)
2. Allow claim-extraction processes to publish their output for broad consumption. This would be a feed of claims found in the media and judged to be of relatively high value for checking. 
3. Allow users to express their desire for specific claims in some content to be checked. Might include offer to pay for results.
4. Allow relationships between claims to be expressed, such as rephrasings to be more precise and context-free vs more terse and context-sensitive, more in agreement vs disagreement with the claim itself, making a broader vs narrower claim, between natural languages, and opposites.
5. Allow structure of a fact-check to be exposed as machine-readable, showing argumentation and secure links to the evidence
6. Allow end-users to express what they feel or know relevant to a claim’s accuracy, in a way that might be reasonable aggregated toward accurate credibility assessment. It's important this not be simply popularity polling; important ideas, when they start, are usually believed by exactly one person.
7. Make it easy to view reviews of related claims from many sources at once, including some data about the sources, such as assessed bias

Some relevant technologies:

* Claim extraction: given some natural language text, recognize fragments that are likely to be checkable claims
* Claim matching: given some claim text, find other claims which are likely to be highly relevant
* Claim interpretation: given some natural language claim text, automatically perform relevant databases searches and calculations to check it

