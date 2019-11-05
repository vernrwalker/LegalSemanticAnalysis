# Annotations

The process of annotating a document (also called "labeling" or "tagging" the text) is a classification task, in which we classify spans of text using categories. We can store such information in a variety of forms, such as XML or JSON files. What is important here is that such annotation captures semantic information about the legal meaning and significance of that text.

For the purpose of **mining arguments** from legal documents, we can think of annotating on three major levels:

1. **Sentence-level Annotation** - such as classifying whole sentences by their rhetorical roles in legal reasoning. Such rhetorical roles include stating _evidence_, stating _legal rules_, stating the _reasoning_ from evidence to conclusion, and stating the _conclusion_ (such as a finding of fact or a ruling of law).
2. **Intra-sentence Annotation** (or sub-sentence annotation) - such as identifying within a sentence those words that signal an attribution of a proposition to a subject. An example is "_The Veteran stated that he experiences flashbacks to his time in combat._" For this evidence sentence, the attribution cue is "_stated that_", the attribution subject is "_The Veteran_", and the attribution object or proposition is "_he experiences flashbacks to his time in combat_".
3. **Inter-sentence Annotation** - such as grouping sentences into meaningful units. An example is linking particular evidence sentences, legal-rule sentences, and reasoning sentences as supporting a particular conclusion (such as a finding of fact or a ruling of law). Such groups of sentences would then be an instance of an _argument or reasoning pattern_.

## Modes of Annotation

There are three primary ways of performing annotation:

1. **Manual or custom-made annotation** by annotation specialists, people trained to annotate text correctly, using protocols. Such annotation is essential for:
    - experimenting with and evaluating new semantic categories for analysis;
    - creating datasets used to develop new analytics for automatic annotation;
    - writing and evaluating scripts for automatic annotation; and
    - training and testing machine learning models.
2. **Automatic annotation**, using analytics. Such annotation is essential for efficiently adding new annotated documents to a dataset, which can be used to scale up a web application.
3. **Hybrid systems** using a mix of manual and automatic annotation.
