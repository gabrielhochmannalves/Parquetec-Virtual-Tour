# 🏛️ Tour Virtual - Ciência da Computação (Itaipu Parquetec)

Ferramenta interativa de orientação espacial desenvolvida para o curso de **Ciência da Computação da UNIOESTE**.

Este projeto visa auxiliar especificamente os **calouros e novos alunos** a localizarem os laboratórios, salas de aula e setores administrativos essenciais do curso dentro do complexo Itaipu Parquetec.

---
## 🎯 Objetivo do Projeto
Resolver a dificuldade de localização enfrentada pelos novos estudantes devido à ampla estrutura do parque, provendo uma simulação virtual onde é possível conhecer previamente o trajeto até pontos chave, como:
- **Laboratórios de Informática e Pesquisa** (Ex: LabCG).
- **Secretaria Acadêmica e Coordenação.**
- **Blocos de Sala de Aula.**
---
## 🚀 Funcionalidades
- **Navegação em Primeira Pessoa:** Controle intuitivo (WASD + Mouse) para explorar os corredores e salas.
- **Visualização 360º:** Renderização de fotos esféricas dos ambientes reais do curso.
- **Pontos de Interesse (Hotspots):** Interação com equipamentos ou salas para visualizar informações sobre horários e finalidades.
---
## 🛠️ Stack Tecnológica
Este projeto utiliza uma arquitetura moderna e limpa ("Clean Slate"), desenvolvida do zero para garantir performance e manutenibilidade:

- **Engine:** Unity 6 (LTS)
- **Render Pipeline:** Universal Render Pipeline (URP) - Foco em performance.
- **Input System:** Novo sistema de eventos e controle da Unity.
- **Linguagem:** C# (.NET Standard 2.1)
---
## 📂 Estrutura do Repositório
O código fonte segue o padrão de organização por domínios:

- `Assets/_Project/`: Diretório raiz do projeto.
    - `Art/`: Fotos 360, materiais e assets visuais.
    - `Code/`: Scripts de navegação e lógica de interação.
    - `Scenes/`: Cenários mapeados do curso.
---
## 🎮 Como Executar (Desenvolvimento)
1. Certifique-se de ter o **Unity 6 (LTS)** instalado.
2. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/Parquetec-Virtual-Tour.git](https://github.com/gabrielhochmannalves/Parquetec-Virtual-Tour.git)
3. Abra o projeto via Unity Hub. 
4. Execute a cena `Main` localizada em `Assets/_Project/Scenes`.
---

**Desenvolvedor:** Gabriel Hochmann Alves

**Instituição:** UNIOESTE - Universidade Estadual do Oeste do Paraná

**Vinculação:** Estágio Supervisionado - Laboratório de Computação Gráfica (LabCG)

**Supervisora:** Profa. Dra. Fabiana Frata Furlan Peres