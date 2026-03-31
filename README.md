# 📋 DocAtivo

> Transforme relatórios **SIGA/ATFA012** em planilhas Excel inteligentes — direto no navegador, sem instalar nada.

![DocAtivo](https://img.shields.io/badge/DocAtivo-v1.0-0F7490?style=for-the-badge&logo=files&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-ativo-1E7C45?style=for-the-badge&logo=github&logoColor=white)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-0F2044?style=for-the-badge)
![100% Browser](https://img.shields.io/badge/100%25-no%20navegador-B45309?style=for-the-badge)

---

## ✨ O que é

**DocAtivo** é uma ferramenta web gratuita desenvolvida para o **Sistema FIEPI / SESI DR/PI**. Ela lê o PDF exportado do sistema SIGA (relatório ATFA012) e gera automaticamente uma planilha Excel organizada com dashboard, filtros e análises — tudo processado no próprio navegador, sem enviar dados para nenhum servidor.

---

## 🖥️ Acesse

```
https://seu-usuario.github.io/docativo
```

---

## 🎯 Como usar

```
1. Abra o site
2. Arraste o PDF exportado do SIGA/ATFA012
3. Veja a prévia dos dados na tela
4. Clique em "Baixar .xlsx"
```

Simples assim. Sem cadastro, sem instalação, sem limite.

---

## 📊 O que é gerado

A planilha Excel contém **4 abas**:

| Aba | Conteúdo |
|-----|----------|
| 📊 Dashboard | Resumo geral, distribuição por filial e ranking de marcas |
| 📋 Inventário Completo | Todos os registros com filtros automáticos |
| ✅ Ativos | Somente equipamentos em uso |
| ❌ Baixados | Somente equipamentos baixados |

Cada registro contém os campos: **Filial**, **Descrição**, **Marca** (detectada automaticamente), **BTUs**, **Grupo**, **Código do Bem**, **Endereço**, **Data de Aquisição**, **Data de Baixa**, **Item** e **Status**.

---

## 🔍 Campos extraídos automaticamente

- ✅ Código e nome da filial
- ✅ Descrição completa do bem
- ✅ Marca detectada (Carrier, Springer, Midea, Komeco, Elgin, Consul, Electrolux, Gree, Agratto, Silvermax, Philco e outras)
- ✅ Capacidade em BTUs
- ✅ Endereço / localização
- ✅ Datas de aquisição e baixa
- ✅ Status: **Ativo** ou **Baixado**

---

## 🔒 Privacidade

> Nenhum dado é enviado para servidores externos.
> Todo o processamento acontece localmente no seu navegador.

O PDF é lido pela biblioteca [PDF.js (Mozilla)](https://mozilla.github.io/pdf.js/) e a planilha é gerada pela biblioteca [SheetJS](https://sheetjs.com/) — ambas executadas 100% no cliente.

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|------------|-----|
| HTML / CSS / JavaScript | Interface e lógica |
| [PDF.js 3.11](https://mozilla.github.io/pdf.js/) | Extração de texto do PDF |
| [SheetJS 0.18](https://sheetjs.com/) | Geração do arquivo .xlsx |
| GitHub Pages | Hospedagem gratuita |

---

## 📁 Estrutura do repositório

```
docativo/
└── index.html      ← aplicação completa (arquivo único)
└── README.md       ← este arquivo
```

---

## 🚀 Como publicar sua própria versão

1. Faça um **fork** deste repositório
2. Vá em **Settings → Pages**
3. Em *Branch*, selecione `main` e clique **Save**
4. Acesse `https://seu-usuario.github.io/docativo`

---

## 📄 Compatibilidade

Desenvolvido e testado para o relatório **SIGA/ATFA012/v.12** do Sistema FIEPI.

Funciona nos navegadores:

![Chrome](https://img.shields.io/badge/Chrome-✓-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Edge](https://img.shields.io/badge/Edge-✓-0078D7?style=flat-square&logo=microsoftedge&logoColor=white)
![Firefox](https://img.shields.io/badge/Firefox-✓-FF7139?style=flat-square&logo=firefox&logoColor=white)

---

## 📝 Licença

Distribuído sob a licença **MIT**. Livre para usar, modificar e distribuir.

---

<div align="center">
  Feito com 💙 para o <strong>Sistema FIEPI / SESI DR/PI</strong>
</div>
