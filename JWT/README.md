# JWT

- [What is jwt](https://github.com/Stakcery/Web-Security/blob/main/JWT/data/JWT%E7%AE%80%E8%A6%81%E4%BB%8B%E7%BB%8D.md)?
  - Description: A brief introduction to jwt.
- [A simple unencrypted problem](https://github.com/Stakcery/Web-Security/blob/main/JWT/data/%E4%B8%80%E4%B8%AA%E7%AE%80%E5%8D%95%E7%9A%84%E6%97%A0%E5%8A%A0%E5%AF%86%E9%A2%98%E7%9B%AE.md)
  - Description: A brief introduction to jwt.
- [The signature algorithm can be modified to none(CVE-2015-2951)](https://github.com/Stakcery/Web-Security/blob/main/JWT/data/%E7%AD%BE%E5%90%8D%E7%AE%97%E6%B3%95%E5%8F%AF%E8%A2%AB%E4%BF%AE%E6%94%B9%E4%B8%BAnone.md)
  - Description: The signature algorithm can be modified to none to disable signature checks
- [Weak Key](https://github.com/Stakcery/Web-Security/blob/main/JWT/data/%E5%AF%86%E9%92%A5%E5%BC%B1%E5%8F%A3%E4%BB%A4.md)
  - Description: The generation key of the algorithm is a weak key
- [Blasting Key](https://github.com/Stakcery/Web-Security/blob/main/JWT/data/%E7%88%86%E7%A0%B4%E5%AF%86%E9%92%A5.md)
  - Description: Sometimes we can blast the key of the algorithm

- [Public and private key leakage](https://github.com/Stakcery/Web-Security/blob/main/JWT/data/%E5%85%AC%E7%A7%81%E9%92%A5%E6%B3%84%E9%9C%B2.md)
  - Description: Security problems caused by leakage of public and private keys of algorithms
- [Key obfuscation attack(CVE-2016-5431)](https://github.com/Stakcery/Web-Security/blob/main/JWT/data/%E5%AF%86%E9%92%A5%E6%B7%B7%E6%B7%86%E6%94%BB%E5%87%BB.md)
  - Description: Some libraries use the same variable name for the key used to sign/verify HMAC symmetric encryption and the key containing the public key used to verify RSA signed tokens