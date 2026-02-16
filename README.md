
# 🎧 VibeCheck AI

### Chatbot Musical com Inteligência Artificial

---

* Bernardo Luiz Silva Edmundo
* João Lucas Torquato de Faria
* Matheus Rocha Nogueira 
* Pedro Henrique Esperidião Aureliano 
* Rafael Araújo Pace 

---
## Visão Geral

O **VibeCheck AI** é um chatbot musical inteligente que interpreta o estado emocional e o contexto do usuário para recomendar automaticamente playlists do Spotify de forma personalizada.

Diferente das buscas convencionais baseadas em palavras-chave, o VibeCheck AI entende frases completas e emoções, oferecendo uma experiência musical muito mais intuitiva e eficaz.

> Você não escolhe a música.
> Você expressa o que sente — e o sistema escolhe por você.

---

## Objetivo

Criar uma experiência musical automatizada baseada em inteligência artificial, onde o usuário conversa em linguagem natural e recebe recomendações personalizadas sem precisar procurar playlists manualmente.

---

## Público-Alvo

Este projeto atende desde usuários comuns até soluções corporativas:

* 🎓 Estudantes
* 💪 Atletas
* 🧘 Pessoas ansiosas
* ☕ Restaurantes e cafés
* 🚗 Viajantes
* 💼 Profissionais
* 🎧 Entusiastas musicais

---

## Como Funciona

O funcionamento do VibeCheck AI é simples e eficiente:

### 1. Entrada do Usuário

O usuário escreve livremente:

> "Estou cansado, mas preciso estudar"

### 2. Processamento Backend

A mensagem é enviada para o backend em Python (Flask).

### 3. Inteligência Artificial

O backend repassa a mensagem para um modelo de IA (Google Gemini) que interpreta:

* Emoção
* Contexto
* Intenção

### 4. Classificação de Vibe

A IA identifica a vibe mais adequada:

> foco, relax, energia, romance...

### 5. Banco de Playlists

O sistema busca a vibe no banco de dados JSON.

### 6. Resposta Automática

A playlist é exibida diretamente no navegador via Spotify Embed.

---

## Tecnologias Utilizadas

### Backend

* Python 3
* Flask
* Google Gemini API
* Regex
* dotenv
* JSON Database

### Frontend

* HTML5
* CSS3
* JavaScript ES6+
* Spotify Embed
* Lucide Icons

---

## Estrutura do Projeto

```
VibeCheck/
│
├── app.py              # Backend Flask
├── vibes_db.json       # Banco de playlists
├── index.html          # Interface web
├── style.css           # Estilo visual
├── script.js           # Lógica do frontend
├── .env                # API Key (não versionar)
└── README.md
```

---

## Segurança

* A chave da API nunca é exposta no código
* Gerenciada através de arquivo `.env`
* Sistema possui tratamento de erros
* Backend protegido por CORS
* Validação de entradas do usuário
* Monitoramento de status do servidor

---

## Diferenciais

✅ IA emocional
✅ Zero busca manual
✅ Multi-vibes por frase
✅ Interface moderna
✅ Player integrado
✅ Código modular
✅ Escalável
✅ Alto potencial comercial

---

## Modelo de Produto

O VibeCheck AI pode ser comercializado como:

* Aplicação Web
* App Mobile
* API pública
* Produto corporativo
* Solução white-label
* Projeto SaaS

---

## Como Executar Localmente

### 1. Clone o repositório

```bash
git clone https://github.com/pedroEKS/VerticalChatbot-IA-2025-02.git
cd VerticalChatbot-IA-2025-02
```

---

### 2. Crie o arquivo `.env`

```env
GEMINI_API_KEY= SUA_CHAVE_AQUI
```

---

### 3. Instale as dependências

```bash
pip install flask flask-cors python-dotenv google-generativeai
```

---

### 4. Execute o backend

```bash
python app.py
```

O servidor será iniciado em:

```
http://127.0.0.1:5000/
```

---

### 5. Rode o frontend

Abra o arquivo `index.html` no navegador ou utilize Live Server.

---

## Futuras Melhorias

* Login com Spotify
* Criação dinâmica de playlists
* Machine Learning personalizado
* Análise de humor
* Mobile App
* Histórico do usuário
* Dashboard administrativo

---


## Licença

Este projeto é de uso educacional e pode ser adaptado para fins comerciais conforme acordo entre as partes.

---

