📘 Introdução

Este documento apresenta os requisitos funcionais, não funcionais e regras de negócio do sistema Descarte Vivo, solução digital que visa auxiliar o gerenciamento de reciclagem, pontos de coleta e entregas de resíduos, promovendo sustentabilidade e contribuindo com o ODS 11 – Cidades e Comunidades Sustentáveis.


✅ Requisitos Funcionais (RF)
Código	Requisito Funcional	
RF01	O sistema deve permitir login e autenticação de usuários via JWT.	
RF02	O sistema deve permitir cadastro de novos usuários.	
RF03	O sistema deve permitir CRUD completo de usuários (listar, criar, editar e excluir) — somente para perfil ADMIN.	
RF04	O sistema deve permitir o cadastro de pontos de coleta.	
RF05	O sistema deve listar os pontos de coleta cadastrados.	
RF06	O sistema deve permitir o registro de entregas com peso e tipo.	
RF07	O sistema deve listar todas as entregas registradas.	
RF08	O sistema deve disponibilizar um dashboard com totais agregados (peso, número de entregas).	
RF09	O sistema deve permitir que cada usuário visualize seu histórico de entregas.	
RF10	O sistema deve validar os campos antes de salvar dados, exibindo mensagens claras de erro.	
RF11	O sistema deve registrar data e hora de criação dos registros.	
RF12	O sistema deve permitir deploy e acesso remoto via navegador.	
RF13	O sistema deve disponibilizar documentação oficial da API no repositório GitHub.	
RF14	O sistema deve registrar validação real com público alvo e documentar seu feedback.	

🚫 Requisitos Não Funcionais (RNF)
Código	Requisito Não Funcional	
RNF01	O sistema deve utilizar segurança JWT e criptografia bcrypt para senhas.
RNF02	O sistema deve retornar respostas API em até 2 segundos.
RNF03	O sistema deve ser responsivo para desktop, tablet e mobile.
RNF04	O sistema deve possuir arquitetura REST e repositório Git organizado.
RNF05	O sistema deve ser atualizado e versionado utilizando GitHub.	
RNF06	O deploy deve ser realizado em ambiente escalável (Railway / Vercel).
RNF07	O banco de dados deve garantir integridade e consistência referencial.
RNF08	O sistema deve registrar logs em caso de exceção e retornar mensagens amigáveis.	
RNF09	A solução deve ser capaz de suportar crescimento futuro de usuários.
RNF10	O sistema deve seguir padrões modernos de design de interface e boa usabilidade.	