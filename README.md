# Real-Time-Domain-Adaptation-in-Image-Segmentation
This repository includes the full code and the paper of the project for the final exam of "Machine learning and Deep learning" course @ Politecnico di Torino

## Code
The code contains:

1. An implementation of a real-time semantic segmentation network, BiSeNet (Bilateral Segmentation Network), that can exploit two different backbones, ResNet-101 or ResNet-18;
2.  Unsupervised domain adaptation strategy based on adversarial learning;
3.  A light version of the discriminator using depth-wise separable convolutions;
4.  creation of pseudo-labels with an unsupervised learning technique, in which a teacher model from unlabeled images generates pseudo labels, which are then
combined with labeled images to retrain the student model
5. a systematic mechanism for the teacher to correct the bias in its pseudo labels by observing the performance of the student model on the pseudo-labeled dataset, and using it to improve the teacher’s creation of pseudo label
