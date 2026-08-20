# Contribuindo com o NerdShelf

NerdShelf é um projeto pessoal e educacional, construído sob a filosofia **Build-to-Learn**. É mantido principalmente por uma pessoa, mas é open source (licença MIT) e aberto a leitura, estudo, sugestões e contribuições pontuais.

Este documento descreve como o projeto é organizado no dia a dia — mesmo sendo solo, o fluxo abaixo é seguido à risca, porque parte do aprendizado é praticar processos que funcionam em equipe.

---

## 🎯 Filosofia Build-to-Learn

> **O objetivo não é terminar rápido. O objetivo é conseguir continuar.**
> **Uma pequena entrega toda semana é melhor que uma grande entrega uma vez por mês.**

Isso se reflete em como o código e a documentação são produzidos:

- Commits pequenos e frequentes são preferíveis a commits grandes e raros.
- Documentar uma decisão é tão importante quanto implementá-la.
- Errar e registrar o erro (nas revisões semanais) faz parte do processo, não é algo a esconder.

---

## 🌱 Fluxo de trabalho

1. **Toda mudança não-trivial começa por uma Issue** — tarefa semanal do roadmap, bug ou ideia/feature. Use os templates disponíveis em `.github/ISSUE_TEMPLATE/`.
2. **Trabalhe em uma branch**, não direto em `main`:
   - `semana-XX-fase` — trabalho de uma semana do `ROADMAP.md`
   - `feat/nome` — nova funcionalidade
   - `fix/nome` — correção de bug
   - `chore/nome` — manutenção, configuração, tarefas de suporte
   - `docs/nome` — documentação
3. **Abra um Pull Request** da branch para `main` antes de mergear, mesmo trabalhando sozinho. O PR é onde a decisão fica registrada — o *porquê*, não só o *o quê* — e é prática para quando o projeto ganhar outros colaboradores.
4. **Ao fechar uma semana do roadmap**, registre a revisão semanal em `docs/weekly/week-XX.md` (veja `docs/weekly/README.md`).

---

## 📝 Convenção de commits

O projeto segue [Conventional Commits](https://www.conventionalcommits.org/), em inglês:

| Tipo | Uso |
|------|-----|
| `chore` | manutenção, configuração, tarefas que não são código de produto |
| `feat` | nova funcionalidade |
| `fix` | correção de bug |
| `docs` | documentação |
| `refactor` | mudança de código sem alterar comportamento |
| `test` | testes |
| `style` | formatação, sem mudança de lógica |
| `ci` | integração/entrega contínua |

Exemplos usados no próprio `ROADMAP.md`:

```
chore: initialize project documentation and workflow
feat: create application shell
feat: establish ui component foundation
```

---

## 🐛 Como abrir uma Issue

- **Tarefa semanal** — planejar ou acompanhar a entrega de uma semana do roadmap.
- **Bug** — algo quebrado, incluindo erros em documentação ou links.
- **Feature/ideia** — uma sugestão de funcionalidade ou melhoria.

Use o template correspondente em `.github/ISSUE_TEMPLATE/`. Se nenhum template servir, uma issue em branco também é aceita.

---

## 🔀 Como abrir um Pull Request

- Referencie a Issue relacionada (`Closes #N`).
- Preencha o template de PR: o que foi feito, por quê, e o que foi aprendido no processo.
- Nesta fase do projeto (ainda sem CI configurado) a validação é feita por revisão manual/self-review antes do merge.

---

## 👥 Contribuições externas

Sugestões e contribuições de terceiros são bem-vindas. Para mudanças de código, comece por uma Issue para alinhar o escopo antes de investir tempo em um PR. Mantenha o tom respeitoso e didático — este é, antes de tudo, um projeto de aprendizado.

Não há um Code of Conduct formal ainda; isso pode ser adicionado no futuro caso o projeto cresça.

---

## 📚 Referências

- [README.md](README.md) — visão geral do projeto
- [ROADMAP.md](ROADMAP.md) — plano de fases semanais
- [LICENSE](LICENSE) — licença MIT
- [docs/README.md](docs/README.md) — organização da documentação
