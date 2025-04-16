# Apresentação da Ferramenta Ansible

Este repositório contém uma apresentação e uma demonstração prática da ferramenta **Ansible**, desenvolvida por:

- Ana Virgínia  
- André Cunha  
- Gabriela Mendes  
- João Henrique Xavier  

## 📌 Sobre o Projeto

O objetivo deste repositório é apresentar os conceitos fundamentais do **Ansible** e demonstrar sua aplicação prática através de um exemplo funcional de provisionamento de servidor com **NGINX**.

---

## 📁 Estrutura


- `hosts`: arquivo de inventário onde você deve configurar os IPs ou domínios das máquinas que serão gerenciadas.
- `provisionamento_nginx.yml`: playbook do Ansible para instalar e configurar o NGINX nas máquinas remotas.

---

## ✅ Pré-requisitos

Antes de executar o projeto, é necessário ter:

- Python 3 instalado
- Ansible instalado (`pip install ansible`)
- Acesso SSH às máquinas remotas com permissões adequadas
- Chave SSH configurada ou senha habilitada

---

## 🚀 Como rodar o sistema

**Clone o repositório:**

```bash
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/anavirginianery/ansible-sysadmin.git)
cd ansible-sysadmin/ansible-demo
```

### 🛠️ Configuração e Execução

**Edite o arquivo `hosts`** com os endereços IP ou nomes das máquinas que deseja gerenciar:

```ini
[webservers]
<ip_da_vm> ansible_user=seu_usuario
```

**Execute o playbook:**

```bash
ansible-playbook -i hosts provisionamento_nginx.yml
```

## 📚 Cursos Gratuitos de Ansible

Abaixo estão algumas opções de cursos gratuitos para quem deseja aprofundar os conhecimentos em Ansible:

- [Curso gratuito da Red Hat sobre Ansible (em português)](https://www.redhat.com/pt-br/blog/new-free-ansible-course)  
  Curso introdutório oficial da Red Hat, com foco em automação de infraestrutura.

- [Cursos gratuitos de Ansible na Udemy](https://www.udemy.com/pt/topic/ansible/free/)  
  Lista de cursos gratuitos disponíveis na plataforma Udemy, em diversos idiomas.

Explore esses conteúdos para complementar sua prática e obter uma base sólida sobre a ferramenta!

