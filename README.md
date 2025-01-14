# Web Diary using Python+Django

Diário virtual feito com Python e Django

<img src="./assets/capa.png" alt="Site" width="900">

**🇧🇷 Português**

## 📝 Descrição

Este projeto é um estudo e demonstra como criar um **ransomware básico** para entender a funcionalidade e os **princípios de criptografia**. Este repositório é destinado exclusivamente para fins educacionais.


## ❓ O que foi feito

Criação de um ransomware básico utilizando **Python**.
Implementação de uma funcionalidade para criptografar arquivos no diretório de destino. Adição de um mecanismo para gerar uma "chave de descriptografia". Testes com diretórios de exemplo para validar a eficácia do código.

**encrypter.py:**

Objetivo: Criptografar um arquivo para torná-lo inacessível sem a chave correta.

Processo:
- Abrir o arquivo: Lê os dados originais (ex.: teste.txt).
- Excluir o arquivo original: Remove o arquivo para impedir acesso ao conteúdo original.
- Criptografar: Usa a chave testeransomwares com o algoritmo AES (modo CTR) para criptografar os dados.
- Salvar como criptografado: Cria um novo arquivo com extensão .ransomware.

**decrypter.py**

Objetivo: Reverter o processo de criptografia e restaurar o arquivo original.

Processo:
- Abrir o arquivo criptografado: Lê os dados de um arquivo já criptografado (ex.: teste.txt.ransomwaretroll).
- Descriptografar: Usa a mesma chave testeransomwares para decifrar os dados.
- Excluir o arquivo criptografado: Remove o arquivo criptografado.
- Restaurar o arquivo: Cria um novo arquivo com o conteúdo descriptografado (ex.: teste.txt).


## 🔥 Resumo

**Linguagem**

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=black)

**Ambiente**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)

**Arquivos**

- *decrypter.py* (decriptador)
- *encrypter.py* (encriptador)
- *teste.txt* (texto descriptografado)
- *teste.txt.ransomware* (texto criptografado)

## 🖥 Como usar

Clone este repositório:
```bash
git clone https://github.com/JSalvadorNET/basic-ransomware-creator  
cd basic-ransomware-creator 
```
Certifique-se de que você tem Python 3 instalado.
Instale as dependências necessárias (se houver).

Para criptografar o arquivo teste.txt:
```bash
python encrypter.py
```
Para descriptografar o arquivo teste.txt.ramsonware:
```bash
python decrypter.py
```

##

**🇺🇸 English**

## 📝 Description

This project is a study that demonstrates how to create a basic ransomware to understand its functionality and the principles of encryption. This repository is intended exclusively for educational purposes.


## ❓ What was done

Development of a basic ransomware using **Python**. Implementation of functionality to encrypt files in the target directory. Addition of a mechanism to generate a "decryption key." Testing with example directories to validate the code's effectiveness.

**encrypter.py:**

Objective: Encrypt a file to make it inaccessible without the correct key.

Process:
- Open the file: Reads the original data (e.g., teste.txt).
- Delete the original file: Removes the file to prevent access to the original content.
- Encrypt: Uses the key testeransomwares with the AES algorithm (CTR mode) to encrypt the data.
- Save as encrypted: Creates a new file with the .ransomware extension.

**decrypter.py**

Objective: Reverse the encryption process and restore the original file.

Process:
- Open the encrypted file: Reads the data of an already encrypted file (e.g., teste.txt.ransomware).
- Decrypt: Uses the same key testeransomwares to decrypt the data.
- Delete the encrypted file: Removes the encrypted file
- Restore the file: Creates a new file with the decrypted content (e.g., teste.txt).


## 🔥 Summary

**Programming language**

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=black)

**Environment**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)

**Files**

- *decrypter.py* (decryption tool)
- *encrypter.py* (encryption tool)
- *teste.txt* (decrypted text)
- *teste.txt.ransomware* (encrypted text)

## 🖥 How to use

Clone this repository:
```bash
git clone https://github.com/JSalvadorNET/basic-ransomware-creator  
cd basic-ransomware-creator 
```
Ensure that you have Python 3 installed. Install any necessary dependencies (if applicable).

To encrypt the file teste.txt:
```bash
python encrypter.py
```
To decrypt the file teste.txt.ransomware:
```bash
python decrypter.py
```




Open a browser and access "http://localhost:5050" to view the fake page. Enter credentials to see what the tool captures ;)


<img src="Phishing-linux/assets/facebook-page.png" alt="Facebook" width="900">
