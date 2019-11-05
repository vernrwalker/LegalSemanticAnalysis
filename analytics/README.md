# Analytics

One goal is to deploy useful web applications that can assist lawyers or non-lawyers in filing successful claims (e.g.,claims for veterans' disability benefits, or claims for compensation for vaccine-related injuries, or claims in landlord-tenant disputes). One way to provide such assistance is through open-source software **analytics** that are developed and evaluated using [**annotations**](https://vernrwalker.github.io/LegalSemanticAnalysis/annotations/) that encode semantic information that is legally significant.

Once an adequate quantity of useful annotations becomes available, it can be used to develop analytics in various ways. Depending upon the desired "use case" (web application functionality), we might develop and evaluate analytics using various tools, such as:

1. **Rule-based scripts**, which use linguistic features to automatically annotate (label, tag, classify) spans of text within the legal document;
2. **Traditional machine learning (ML) algorithms**, such as regression algorithms (e.g., logistic regression) or instance-based algorithms (e.g., support vector machines - SVMs);
3. **Deep learning (DL) models**, trained using neural network architectures that may contain many layers; or
4. Other technologies not yet developed.
Various tools can also be combined into a hybrid system, depending upon the analytic task and the desired use case.

**Analytics** that perform at acceptable levels can assist a user by:

* locating and retrieving _similar cases_, which addressed similar legal issues, in similar procedural postures, with similar types of evidence or legal rules;
* _automatically annotating_ decisions from those similar cases, drawing the user's attention to those groups of sentences that show the relevant reasoning; and
* recommending to the user ways to _develop new arguments_ for the new case, based on those past similar cases.

In order to provide the most assistance, we should also develop such analytics with adequate [documentation](https://vernrwalker.github.io/LegalSemanticAnalysis/documentation/).
