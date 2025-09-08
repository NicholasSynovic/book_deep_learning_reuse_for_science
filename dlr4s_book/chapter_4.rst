###########
 Chapter 4
###########

******************************
 Deep Learning Reuse Overview
******************************

Much of this work is copy pasted from this paper:
https://arxiv.org/pdf/2404.16688

Conceptual Reuse: Replicate and reengineer the algorithms, model
architectures, or other concepts described in academic literature and
similar sources, integrating the replication into new projects. An
engineer might do this because of licensing issues or if they are
required to use a particular deep learning framework (eg TensorFlow) but
are reusing ideas previously realized in another deep learning framework
(\eg PyTorch)~\cite{Intro2TFMG}. This paradigm is related to
Sommerville's notion of abstraction reuse, where an engineer reuses
knowledge but not code directly. This paradigm is also related to
reproducibility in the scientific sense, since an engineer independently
confirms the reported results of a proposed technique.

Adaptation Reuse: Leverage existing DNN models and adapt them to solve
different learning tasks. An engineer might do this using several
techniques, such as transfer learning or knowledge distillation. This
form of reuse is suitable if there is a publicly available
implementation of an appropriate model (a pre-trained model). This
paradigm is related to Sommerville's notion of object/component reuse,
since an engineer must identify existing models suited for a purpose and
then customize them for a different task.

Deployment Reuse: Convert and deploy pre-trained DNN models in different
computational environments and frameworks. This form of reuse is
suitable if there is a perfect fit for the engineer's needs, viz. a DNN
trained on the engineer's desired task (eg demonstrating proof of
concept in a hackathon). This paradigm is related to Sommerville's
notion of system reuse, since an engineer is reusing an entire model
(including its training) and deploying it in the appropriate context.
Deployment often requires the conversion of a DNN from one
representation to another, followed by compilation to optimize it for
hardware.
