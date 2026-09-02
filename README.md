# 🖥️ Rack de Servidor 3D (Blender)

Projeto de modelagem 3D procedural de um **Rack / Gabinete de Servidor** desenvolvido no Blender com técnicas não destrutivas.

---

## 🎯 Objetivo & Modificadores Utilizados

Demonstrar a aplicação prática e procedural dos seguintes modificadores:

* **`Mirror`:** Simetria estrutural do gabinete, colunas e furações dos trilhos.
* **`Array`:** Repetição de elementos como baias de servidores, grelhas e parafusos.
* **`Boolean`:** Recortes para ventilação, encaixes de baias e entradas de cabos.
* **`Solidify`:** Espessura de chapas e superfícies metálicas. 

---
<img width="587" height="480" alt="image" src="https://github.com/user-attachments/assets/b847d46e-9609-4222-91c5-890a0b35e273" />



## 💡 Por que utilizei cada função?

* **`Mirror`:** Utilizado para garantir a simetria da estrutura. A partir do momento em que uma coluna foi modelada, utilizar o *Mirror* para gerar as outras três me poupou bastante tempo.
* **`Array`:** Assim como o *Mirror*, utilizei o *Array* para automatizar a repetição padronizada dos elementos na estrutura.
* **`Boolean`:** Utilizado para realizar os recortes e vazados (como a ventilação do gabinete). Foi, sem dúvidas, a parte mais desafiadora da modelagem.
* **`Solidify`:** Função que não conhecia previamente, mas, foi a solução ideal para dar espessura aos planos e permitir a aplicação do *Boolean* sem quebrar a malha, transformando as superfícies em uma estrutura 3D funcional.

---

## 📁 Entrega

* **Arquivo:** `Kaique_RackServidor.blend`
* **Visualização:** Abra o arquivo no Blender e selecione os objetos para inspecionar a pilha de modificadores na aba **Properties > Modifiers**.
