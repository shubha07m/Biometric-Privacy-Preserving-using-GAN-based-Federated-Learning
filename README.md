# 🌟 Privacy Preserving of Biometric Templates using Generative Adversarial Network-based Secure Cryptography 🌟

---

## ✨🎉 **Exciting News!** 🎉✨

We are thrilled to announce that our paper:

### **“A Secure and Private Ensemble Matcher Using Multi-Vault Obfuscated Templates”**

will be presented at the upcoming **special session on Generative AI for Futuristic Biometrics** at **IJCB 2024** in Buffalo, NY, USA! 🚀

✨🌟✨🌟✨🌟✨🌟✨

**Stay tuned for more updates!**

---

## **Paper Highlights**

Generative AI has transformed machine learning by offering unprecedented realism, diversity, and efficiency in data generation, with significant implications for biometric security. This paper introduces a novel method using Generative AI, specifically GANs, to enhance biometric template security.

- The approach obfuscates biometric data with synthetic facial images, creating **n sub-templates** with **m randomized "chaff points"** for identity protection.
- Tested on the **AT&T, GT, and LFW face datasets**, the method achieved **ROC areas under the curve of 0.99, 0.99, and 0.90**, respectively.
- The results demonstrate that the method maintains **high accuracy** and reasonable computational complexity while significantly enhancing security and privacy.

---

![Generative AI](https://github.com/shubha07m/Federated-biometric-privacy/blob/main/hashpic.png)

The system employs GAN-based approaches, specifically using **StyleGAN2**, to generate chaff points in the form of realistic human faces. These synthetic faces are integrated with genuine biometric data to create obfuscated templates.

- By blending these realistic but fake faces with actual biometric features, the system enhances security, making it extremely challenging for attackers to differentiate between real and artificial data points.
- This approach adds a robust layer of protection, preventing unauthorized reconstruction or misuse of the original biometric data.

---

![Data Distribution](https://github.com/shubha07m/Federated-biometric-privacy/blob/main/dist1.png)

One of the key achievements of this method is its ability to maintain **high accuracy in authentication** despite the obfuscation and distribution of biometric templates. The **ensemble matching technique**, which involves collectively using the data from all vaults, ensures reliable verification without compromising performance.

- This system's design demonstrates a successful balance between **security, privacy, and accuracy**, marking a significant advancement in the field of biometric authentication.

---

## **Preprint Available**

- [Read the Preprint](https://github.com/shubha07m/Biometric-Privacy-Preserving-using-GAN-based-Federated-Learning/blob/main/ijcb_arxiv.pdf)

---

## **Cite Our Work**

If you like our work, please consider citing it as follows:

```bibtex
@article{gilkalaye2024secure,
  title={A secure and private ensemble matcher using multi-vault obfuscated templates},
  author={Gilkalaye, Babak Poorebrahim and Mukherjee, Shubhabrata and Derakhshani, Reza},
  journal={arXiv preprint arXiv:2404.05205},
  year={2024}
}
