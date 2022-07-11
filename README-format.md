En | [Zh](https://github.com/P-KB-O/good-first-repo/blob/main/README-format.zh.md)

## stand-off format

[BioNLP Shared Task 2011](https://2011.bionlp-st.org/bionlp-shared-task-2011/file-formats) | [BioNLP-ST 2013](https://2013.bionlp-st.org/file-formats)

All annotations IDs consist of a single upper-case character identifying the annotation type and a number. The initial ID characters relate to annotation types as follows:

T : text-bound annotation (entity / event trigger)

E : event

M : event modification

R : relation

N : normalization (external reference) (added in `BioNLP-ST 2013`)

Additionally, an asterisk ("*") can be used as a placeholder for an ID in special cases in the gold data, but should not be used in system output.

### Entity annotation files (.a1)

These files contain annotation for given entities found in the text. All entity annotations are given a unique ID and are defined by type (e.g. Protein or Chemical) and the span of characters containing the entity mention (represented as a "start end" offset pair).

### Target annotation files (.a2)

These files contain annotation for events, relations, and other related information that is the target for extraction in each task.

include 
1. Event annotations
2. Relation annotations
3. Additional entity annotations
4. Entity equivalence annotations

