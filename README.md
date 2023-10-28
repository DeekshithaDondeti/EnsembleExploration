# EnsembleExploration

https://medium.com/nlplanet/a-model-distillation-survey-7f0e1b56b3cf <br>
https://arxiv.org/pdf/2006.05525.pdf

Purpose of Model Distillation:<br>
Model distillation is used to make large-scale machine learning models practical for real-world applications by transferring knowledge from a complex teacher model to a simpler student model.<br>
<br>
Methods for Model Efficiency:<br>
Apart from model distillation, other methods like parameter pruning, sharing, and low-rank factorization can make models faster and more efficient for predictions by reducing model complexity.<br>
<br>
Knowledge Transfer from Teacher to Student:<br>
In model distillation, knowledge is transferred from a trained teacher model to a student model. This knowledge encompasses both soft class predictions and training data.<br>
<br>
Benefits of Soft Targets:<br>
Soft targets, which include probabilities for multiple classes, can help the student model learn a gradual understanding of different classes and improve generalization.<br>
<br>
MNIST Dataset Experiment:<br>
An MNIST dataset experiment showed that soft targets from a teacher model can transfer a significant amount of knowledge to a distilled student model, even when the teacher model has not seen certain classes during training.<br>
Types of Knowledge in Distillation:<br>
Knowledge can be response-based (last output layer), feature-based (intermediate layers), or relation-based (relationships between layers or data samples).<br>
Distillation Schemes:<br>
Different distillation schemes include offline distillation (sequential teacher-student training), online distillation (simultaneous teacher-student updates), and self-distillation (using the same network for both teacher and student).<br>

