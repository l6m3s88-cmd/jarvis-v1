# Jarvis V1

Web app do Jarvis em Next.js + Supabase.

## 1. Configurar

Copiar `.env.example` para `.env.local` e preencher `NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY` com a chave publicável do projeto Supabase Jarvis.

## 2. Instalar e arrancar

```bash
npm install
npm run dev
```

Abrir http://localhost:3000

## 3. O que já funciona

- Login por magic link do Supabase
- Lista de tarefas de hoje e amanhã
- Microfone no browser
- Reconhecimento de voz pt-PT quando suportado pelo navegador
- Resposta falada com SpeechSynthesis pt-PT
- Comandos ligados à Edge Function `jarvis-command`

## 4. Próximos módulos

- Notícias em tempo real
- Briefing da manhã
- Apagar/editar tarefas por voz
- Voz TTS consistente de qualidade profissional
- Calendário
- App mobile
