# Privacy Preserving of Biometric Templates using Generative Adverserial Network based Secure Cryptography

We introduced an innovative method for biometric authentication that significantly improves security and privacy. By generating multiple obfuscated templates and storing them across different vaults, the system ensures that no single vault contains enough information to reconstruct the user's biometric data. This approach mitigates the risks associated with data breaches and unauthorized access, providing a robust defense against potential attacks. The use of multiple vaults not only disperses the risk but also complicates the efforts of malicious actors attempting to compromise the system.

![alt text](https://github.com/shubha07m/Federated-biometric-privacy/blob/main/hashpic.png)

The system employs GAN-based approaches, specifically using StyleGAN2, to generate chaff points in the form of realistic human faces. These synthetic faces are integrated with genuine biometric data to create obfuscated templates. By blending these realistic but fake faces with actual biometric features, the system enhances security, making it extremely challenging for attackers to differentiate between real and artificial data points. This approach adds a robust layer of protection, preventing unauthorized reconstruction or misuse of the original biometric data.

![alt text](https://github.com/shubha07m/Federated-biometric-privacy/blob/main/dist1.png)

One of the key achievements of this method is its ability to maintain high accuracy in authentication despite the obfuscation and distribution of biometric templates. The ensemble matching technique, which involves collectively using the data from all vaults, ensures reliable verification without compromising performance. This system's design demonstrates a successful balance between security, privacy, and accuracy, marking a significant advancement in the field of biometric authentication.

- [arXiv preprint](https://arxiv.org/abs/2404.05205)

If you like our work, please consider cite it as follows:

@article{gilkalaye2024secure,
  title={A secure and private ensemble matcher using multi-vault obfuscated templates},
  author={Gilkalaye, Babak Poorebrahim and Mukherjee, Shubhabrata and Derakhshani, Reza},
  journal={arXiv preprint arXiv:2404.05205},
  year={2024}
}
