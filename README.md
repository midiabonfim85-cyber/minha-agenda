MINHA AGENDA v4

Correção do fluxo "Esqueci minha senha": usa o método oficial resetPasswordForEmail do cliente Supabase para solicitar o e-mail de recuperação, com redirectTo configurado para a Vercel.

URL de produção:
https://minha-agenda-three.vercel.app

No Supabase:
Site URL:
https://minha-agenda-three.vercel.app

Redirect URL:
https://minha-agenda-three.vercel.app/**

Importante: o serviço SMTP padrão do Supabase Free possui limite de envio muito baixo (atualmente 2 mensagens por hora). Depois de vários testes, aguarde o limite resetar antes de tentar novamente, ou configure SMTP próprio.
