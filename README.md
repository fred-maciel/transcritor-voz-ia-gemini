🎙️ Transcritor e Assistente de Voz com Gemini 2.5 Flash
Descrição: > Este projeto integra a API do Google Gemini (versão 2.5 Flash) para processar transcrições de áudio e gerar respostas inteligentes, convertendo-as de volta em voz usando gTTS. Desenvolvido como parte do desafio prático da DIO.

Tecnologias Utilizadas:

Python (Google Colab)

Google GenAI SDK (Modelos 2.x e 3.x)

gTTS (Google Text-to-Speech)

Destaques Técnicos:

Originalmente este projeto utilizaria o Chatgpt, mas foi necessária a mudança para o Gemini devido ao Chatgpt solicitar pagamento para utilização de tokens.

Implementação de tratamento de erros para limites de cota (429) e rotas de API (404).

Gerenciamento seguro de credenciais usando o Secrets do Colab.

Utilização das versões mais recentes dos modelos generativos do Google (2026).
