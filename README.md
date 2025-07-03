# ⚙️ PythonIP

## 🧾 Descrição

**PythonIP** é uma ferramenta desenvolvida para facilitar a configuração da interface de rede em sistemas operacionais baseados em Python.  
Seu objetivo é simplificar o processo de alteração de IP, DNS e interfaces com opções práticas e automatizadas via um menu interativo.

O comportamento do programa pode ser customizado por meio do arquivo `config.ini`, localizado na pasta do projeto, permitindo ajustes conforme a necessidade do usuário.

---

## 🧩 Funcionalidades

1. **DHCP** – Configura a interface selecionada para obter IP automaticamente.
2. **ADD IP /24** – Adiciona um IP à interface de rede com máscara `255.255.255.0`.
3. **Inserir IP Manual** – Entrada manual de IP, máscara e gateway.
4. **ADD DNS** – Permite adicionar servidores DNS após configurar IPs.
5. **ADD IP AUTO** – Gera um IP automaticamente com base em parâmetros predefinidos no `config.ini` (máscara, gateway, host).
6. **Menu Predefinido** – Submenu que usa "slots" do `config.ini` para configurar interfaces rapidamente.
   - Parâmetros importantes:
     - `INT`: Define qual interface será usada (1 = principal, 2 = secundária).
     - `IP_UNICO`: Se definido como `sim`, limpa os IPs existentes antes de aplicar o novo.
7. **Alterar Interface** – Permite trocar a interface alvo da configuração.
8. **Habilitar/Desabilitar Interface** – Liga ou desliga a interface de rede selecionada.

---

## 🛠️ Pré-requisitos

- Python 3.x
- Permissões de administrador (para aplicar mudanças na rede)
- Sistema operacional compatível (Linux e Windows)

---
