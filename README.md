# PsicoPita | Estuda IA — Transpetro Psicologia

Site independente de preparação para o concurso Transpetro, com visual PsicoPita em azul-petróleo e dourado.

## Funcionalidades disponíveis

- Agenda diária com leitura por páginas e avanço guiado para questões e flashcards.
- Biblioteca com catálogo de 54 materiais, sem distribuição de PDFs de terceiros.
- Leitor integrado para PDFs selecionados pelo próprio estudante, guardados no navegador.
- 80 questões autorais e simulado de 70 questões (10 Português, 10 Inglês e 50 Psicologia).
- Progresso registrado localmente e exportação/importação de dados.
- Configuração opcional de Supabase para sincronização; exige backend configurado.
- Tutor IA em preparação; precisa de backend seguro e chave do provedor.

## Publicar no GitHub Pages

No repositório abra **Settings → Pages → Build and deployment**. Escolha **Deploy from a branch**, selecione **main** e **/(root)**. Salve e aguarde o GitHub confirmar o endereço da implantação.

A aplicação pública está concentrada em `index.html` e não exige compilação. Os PDFs licenciados do Gran Cursos não estão no código do repositório. Não publique seus arquivos de assinatura no GitHub Pages.

## Privacidade

Sem a configuração de um banco de dados, os materiais enviados pelo usuário e o progresso permanecem no navegador/dispositivo. Para sincronização privada é necessário configurar autenticação, armazenamento, regras de acesso e tutor com servidor seguro.

Projeto de estudo independente, não afiliado oficialmente à Transpetro ou ao Gran Cursos.