# Projeto de Rede com VLAN e Inter-VLAN Routing

## Descrição

Este projeto simula uma rede corporativa utilizando VLANs para segmentação de rede e roteamento entre VLANs com a técnica **Router-on-a-Stick**.

A topologia foi desenvolvida no Cisco Packet Tracer, com o objetivo de demonstrar comunicação entre diferentes setores de uma empresa.

---

## Topologia da Rede

* 1 Roteador (R1)
* 2 Switches (SW-CORE e SW-ACCESS)
* 4 Computadores (PCs)
* Conexões trunk entre dispositivos

---

## Segmentação por VLAN

* **VLAN 10 - ADMINISTRATIVO**

  * Rede: 192.168.10.0/24

* **VLAN 20 - TECNOLOGIA**

  * Rede: 192.168.20.0/24

---

## Tecnologias Utilizadas

* VLAN (Virtual LAN)
* Trunk 802.1Q
* Router-on-a-Stick
* Cisco Packet Tracer

---

## Configurações Realizadas

### 🔹 Switches

* Criação de VLANs
* Associação de portas às VLANs
* Configuração de portas trunk

### 🔹 Roteador

* Criação de subinterfaces
* Encapsulation dot1Q
* Atribuição de endereços IP

---

## Comunicação entre Redes

Antes do roteamento:

* ❌ VLAN 10 não se comunicava com VLAN 20

Após configuração do roteador:

* ✅ Comunicação entre VLANs funcionando corretamente

---

## 🧪 Testes Realizados

* Ping entre dispositivos da mesma VLAN ✔
* Ping entre VLANs diferentes ✔

---

## 📸 Topologia
<img width="825" height="394" alt="Captura de tela 2026-03-20 125839" src="https://github.com/user-attachments/assets/dc4c2eaa-e281-46ce-b3cd-72877ed11179" />



---

## Objetivo do Projeto

* Praticar conceitos de redes
* Entender segmentação com VLAN
* Implementar roteamento entre VLANs
* Simular ambiente corporativo

---

## Autor

Projeto desenvolvido por **Ariel Sousa**

---

## Observações

Este projeto foi desenvolvido para fins de aprendizado e prática em redes de computadores.
