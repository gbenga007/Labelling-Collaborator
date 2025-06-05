# Labelling-Collaborator : Combining Vision-Language Models and Weak Supervision for Nuanced Vision Classification Tasks
## Abstract : 
Nuanced-concept image classification tasks often re-
quire substantial labeled data. The labeling process
for such problems is time-consuming and labor-intensive.
While zero-shot methods like Modeling Collaborator have
shown promising results, they generally lack a versatile
open source pipeline for domain-independent, multi-class
fine-grained classification. We are proposing a classifi-
cation pipeline consisting of weak supervision and open-
source Vision Language Models (VLMs) to be employed in
both binary and multi-class nuanced classification prob-
lems. Our proposed pipeline is domain-independent as it
uses knowledge embedded in the pre-training of VLMs. This
eliminates the need for additional fine-tuning for specific
contexts, as required by methods such as AdaptCLIPZS. In
our proposed pipeline, VLMs serve as weak labelers in the
classification tasks, while a Weak Supervision (WS) model
aggregates those labels and produce a set of pseudo labels
(pseudo ground-truth) to train an end classifier. We have
conducted multiple experiments to demonstrate the valid-
ity of the pipeline in both binary and multi-class classifica-
tion tasks. The experimental results have shown that our
proposed pipeline is capable of producing superior results
in both binary and multi-class problems compared to the
state-of-the-art zero-shot classification methods.
![LC_pipeline](https://github.com/user-attachments/assets/6819ffe1-edaf-49ce-99c9-90d8e94af76d)



