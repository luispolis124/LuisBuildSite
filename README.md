# 🌍 LuisBuildSite

Plataforma da comunidade desenvolvida para o compartilhamento de mods, texturas, mapas e conteúdos personalizados para jogos. 

---

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias modernas de desenvolvimento web e nuvem:

* **Frontend / Hospedagem:** [Vercel](https://vercel.com/) (para deploy contínuo, alta performance e rotas rápidas).
* **Banco de Dados / Autenticação:** [Supabase](https://supabase.com/) (para gerenciamento de usuários, upload de arquivos/mods e banco PostgreSQL em tempo real).
* **Framework:** *(Defina aqui se usará React, Next.js, Vue, etc., ex: Next.js / Vite)*

---

## 📦 Funcionalidades Principais

* **Autenticação de Usuários:** Cadastro e login seguros para criadores e jogadores.
* **Upload de Mods e Texturas:** Envio de arquivos compactados e imagens prévias dos conteúdos.
* **Sistema de Busca e Filtros:** Encontre mods por categorias, popularidade ou jogos específicos.
* **Comentários e Avaliações:** Espaço para a comunidade interagir e avaliar os mods publicados.

---

## 🛠️ Como Executar o Projeto Localmente

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/LuisBuildMods.git](https://github.com/SEU-USUARIO/LuisBuildMods.git)
   cd LuisBuildMods

 * Instale as dependências:
   npm install

 * Configure as Variáveis de Ambiente:
   Crie um arquivo .env na raiz do projeto seguindo o modelo do .env.example e adicione as suas chaves do Supabase:
   VITE_SUPABASE_URL=sua_url_do_supabase
VITE_SUPABASE_ANON_KEY=sua_chave_anon_do_supabase

 * Inicie o servidor de desenvolvimento:
   npm run dev

📄 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para contribuir, abrir issues ou sugerir melhorias!
