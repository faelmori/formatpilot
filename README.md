# formatpilot

[![PyPI version](https://img.shields.io/pypi/v/formatpilot.svg)](https://pypi.org/project/formatpilot/)
[![Python versions](https://img.shields.io/pypi/pyversions/formatpilot.svg)](https://pypi.org/project/formatpilot/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://github.com/faelmori/formatpilot/actions/workflows/python-package.yml/badge.svg)](https://github.com/faelmori/formatpilot/actions)
[![Downloads](https://static.pepy.tech/badge/formatpilot)](https://pepy.tech/project/formatpilot)

> Conversão e transformação de textos entre múltiplos formatos (Markdown, LinkedIn, HTML, etc) de forma simples e extensível. Com amor da família Mori!

---

## ✨ Visão Geral

O **formatpilot** é um pacote Python para conversão e transformação de textos entre diversos formatos, como Markdown, HTML e formatos otimizados para LinkedIn. Ideal para desenvolvedores, criadores de conteúdo e automações.

- Conversão de Markdown para LinkedIn
- Conversão de Markdown para HTML
- Conversão de HTML para Markdown
- Fácil extensão para novos formatos
- API simples e intuitiva

## 🚀 Instalação

```bash
pip install formatpilot
```

## 🛠️ Exemplo de Uso

```python
from formatpilot import markdown_to_linkedin

markdown = """
**Texto em negrito**
- Item 1
- Item 2
"""

linkedin_text = markdown_to_linkedin(markdown)
print(linkedin_text)
```

## 📚 Funcionalidades

- `markdown_to_linkedin(markdown_text: str) -> str`: Converte Markdown para formato LinkedIn.
- Classe `LinkedInConverter`: Métodos para conversão entre Markdown, HTML e LinkedIn.

## 🧩 Extensibilidade

Você pode criar seus próprios conversores ou estender as classes existentes para suportar novos formatos de texto.

## 🧪 Testes

```bash
pytest tests/
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

1. Fork este repositório
2. Crie sua branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📄 Licença

MIT © Rafael Mori

## 💌 Contato

- [GitHub](https://github.com/faelmori/formatpilot)
- [faelmori@gmail.com](mailto:faelmori@gmail.com)

---

**Feito com carinho pela família Mori!** ❤️
