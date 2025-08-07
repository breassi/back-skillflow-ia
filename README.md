# 📚 SkillFlow – IA de Aprendizado Preditivo Personalizado

> 🚀 Plataforma inteligente que adapta o conteúdo educacional ao estilo cognitivo de cada pessoa, utilizando IA para transformar o aprendizado em uma jornada personalizada e evolutiva.

![SkillFlow Banner](./docs/assets/banner-skillflow.png)

---

## 📘 Sumário

- [🧩 Visão Geral](#-visão-geral)
- [✨ Funcionalidades](#-funcionalidades)
- [🔬 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [📱 Arquitetura](#-arquitetura)
- [💡 Diferenciais](#-diferenciais)
- [📈 Roadmap](#-roadmap)
- [🔐 Privacidade e Ética](#-privacidade-e-ética)
- [🛠️ Como Contribuir](#️-como-contribuir)
- [🚀 Como Executar Localmente](#-como-executar-localmente)
- [📄 Licença](#-licença)

---

## 🧩 Visão Geral

Cada pessoa aprende de maneira diferente. No entanto, a maioria dos cursos online continua a tratar todos os alunos da mesma forma. O **SkillFlow** resolve esse problema com uma abordagem inovadora:

Uma **plataforma de aprendizado inteligente** que adapta automaticamente o conteúdo, ritmo e formato de ensino de acordo com o desempenho e estilo cognitivo do aluno, tudo isso **em tempo real**.

Através da análise de comportamento, testes A/B e gamificação inteligente, a IA aprende com o aluno e personaliza sua jornada educacional com precisão.

---

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|----------------|-----------|
| 🧠 Detecção de Estilo Cognitivo | Classifica automaticamente se o aluno é visual, auditivo ou cinestésico com base em interações e resultados. |
| 🧪 Testes A/B Automatizados | Variações de conteúdo aplicadas dinamicamente para medir engajamento e retenção. |
| 🔄 Reorganização de Trilhas | A IA adapta a sequência e tipo de conteúdo conforme a absorção de conhecimento. |
| 🎮 Gamificação Inteligente | Pontuações, desafios e recompensas adaptadas ao perfil do aluno. |
| 📈 Dashboard de Progresso | Feedbacks visuais sobre desempenho, tempo, foco e evolução. |
| 🔍 Análise de Engajamento | Identifica quedas de atenção e propõe ajustes no conteúdo. |
| 🤖 IA Adaptativa | Algoritmos de ML que evoluem conforme o comportamento de cada usuário. |

---

## 🔬 Tecnologias Utilizadas

| Área | Tecnologias |
|------|-------------|
| IA/ML | Python, Scikit-Learn, TensorFlow, FastAPI |
| NLP | BERT, spaCy, Transformers |
| Backend | .NET Core 9 (Web API), C# 13 |
| Frontend | Angular 17, TailwindCSS, Chart.js |
| Armazenamento | PostgreSQL (usuários e progresso), Redis (A/B), Firebase |
| DevOps | Docker, GitHub Actions, Kubernetes (opcional) |
| Observabilidade | Serilog, Prometheus, Grafana |
| Segurança | IdentityServer, JWT, Criptografia AES-256 |

---

## 💡 Diferenciais

- ✅ **Aprendizado Adaptativo em Tempo Real**: A IA molda o conteúdo conforme a performance do aluno.
- ✅ **Detecção de Estilos Cognitivos**: Personalização de formatos (vídeo, texto, interação).
- ✅ **Gamificação Dinâmica**: Os desafios se ajustam conforme o engajamento.
- ✅ **Feedback Visual e Cognitivo**: Relatórios e insights sobre foco, retenção e evolução.

---

## 🔐 Privacidade e Ética

A personalização do aprendizado envolve dados sensíveis. O **SkillFlow** adota uma abordagem ética e transparente:

- Consentimento explícito do usuário.
- Armazenamento seguro e criptografado.
- Opção de anonimização de dados.
- A IA não toma decisões punitivas — apenas adaptativas.

---

## 🛠️ Como Contribuir

1. Faça um fork do repositório.
2. Crie uma branch: `git checkout -b feature/minha-feature`
3. Commit suas alterações: `git commit -m "feat: adiciona nova feature"`
4. Faça push: `git push origin feature/minha-feature`
5. Crie um Pull Request 🙌

Contribuições de devs, educadores, psicólogos cognitivos e UX designers são super bem-vindas!

---

## 🚀 Como Executar Localmente

```bash
# Clone o projeto
git clone https://github.com/seu-usuario/dotnet-skillflow-edu.git
cd dotnet-skillflow-edu

# Backend (.NET Core 9)
cd src/Backend/SkillFlow.Api
dotnet restore
dotnet run

# IA Services (Python)
cd ../../ml-services
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend (Angular 17)
cd ../frontend
npm install
npm start

```
---

## ⚠️ Requisitos:

.NET 9 SDK
Node.js 18+
Python 3.10+
Docker 

---

## 📄 Licença
Distribuído sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

## 💙 Agradecimentos
Este projeto nasceu da crença de que ninguém aprende do mesmo jeito — e que a tecnologia deve se adaptar ao ser humano, e não o contrário.

"Ensinar todo mundo do mesmo jeito é como forçar todos os animais a subir em uma árvore." — Albert Einstein (atribuído)

Desenvolvido com propósito por Breno Assis.
