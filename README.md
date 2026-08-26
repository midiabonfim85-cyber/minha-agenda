MINHA AGENDA v3

Esta versão usa diretamente a API do Supabase para o login e banco, evitando dependência do SDK por CDN.

Antes de testar:
1. No Supabase, Authentication > URL Configuration.
2. Site URL:
https://minha-agenda-puw0rgh9f-midi-bonfim.vercel.app
3. Redirect URL:
https://minha-agenda-puw0rgh9f-midi-bonfim.vercel.app/**
4. Salve.

Importante: o serviço de e-mail padrão do Supabase tem limite de envio para testes. Não fique solicitando vários resets.

A aplicação usa somente a Publishable key. Nunca coloque service_role/secret key no navegador.
