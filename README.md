# 🌐 Verificador de Status de IP (Python)

Este projeto é um script simples em Python que verifica se um ou mais endereços IP estão online ou offline utilizando o comando `ping`.

---

## 🚀 Funcionalidades

* 🔍 Verifica se um IP está online
* 📡 Mede o tempo de resposta (latência em ms)
* ❌ Identifica IPs offline
* ⚡ Execução rápida e simples

---

## 🛠️ Tecnologias utilizadas

* Python
* Biblioteca `subprocess`
* Expressões regulares (`re`)

---

## 🧠 Como funciona

O script:

1. Recebe uma lista de IPs
2. Executa um `ping` para cada IP
3. Analisa a resposta do sistema
4. Verifica se o IP está online
5. Extrai o tempo de resposta (ms)
6. Exibe o resultado no terminal

---

## ▶️ Como usar

1. Adicione os IPs no código:

```python
ips = [
    "8.8.8.8",
    "1.1.1.1"
]
```

2. Execute o script:

```bash
python verificador_ip.py
```

---

## 📌 Exemplo de saída

```
8.8.8.8 ONLINE! - 23 ms
1.1.1.1 ONLINE! - 18 ms
192.168.1.1 OFFLINE
```

---

## ⚠️ Observações

* O script foi desenvolvido para ambiente Windows (`ping -n 1`)
* Pode ser necessário adaptar o comando para Linux/Mac (`ping -c 1`)

---

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido para praticar:

* Execução de comandos do sistema via Python
* Manipulação de strings
* Uso de expressões regulares
* Lógica de verificação de status de rede

---

## 🚀 Possíveis melhorias

* Suporte para Linux/Mac
* Interface gráfica (GUI)
* Verificação contínua (monitoramento em tempo real)
* Exportação de resultados para arquivo

---

## 👨‍💻 Autor

Cauã Henrique
Futuro desenvolvedor Back-end 🚀

---

💡 Projeto simples com foco em aprendizado e prática de lógica.
