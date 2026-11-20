# Mark Laser — Landing Pages e Presença Digital

Repositório oficial dos sites institucionais e páginas de conversão da **Mark Laser** hospedados via **GitHub Pages**.

---

## 🌐 Estrutura de URLs & Pastas

| Divisão de Serviço | Caminho no Repositório | URL Final no Domínio |
| :--- | :--- | :--- |
| **Portal Principal** | [`/index.html`](index.html) | `https://www.marklaser.com.br/` |
| **Troféus & Placas de Homenagem** | [`/trofeu/index.html`](trofeu/index.html) | `https://www.marklaser.com.br/trofeu` |
| **Locação de Máquinas para Eventos** | [`/locacao/index.html`](locacao/index.html) | `https://www.marklaser.com.br/locacao` |
| **Marcação a Laser Industrial & B2B** | [`/marcacao/index.html`](marcacao/index.html) | `https://www.marklaser.com.br/marcacao` |

---

## 🛠️ Informações Técnicas para o Webdesigner / DNS

### 1. Domínio Personalizado (CNAME)
O arquivo `CNAME` na raiz do repositório está configurado como:
```text
www.marklaser.com.br
```

### 2. Apontamento de DNS (Zona de DNS no Registro.br, Cloudflare, etc.)

Para ativar o domínio com suporte a SSL gratuito automático pelo GitHub Pages:

#### A) Entrada CNAME (para subdomínio `www`):
* **Nome / Host:** `www`
* **Tipo:** `CNAME`
* **Destino / Valor:** `souandrenunes.github.io.`

#### B) Entradas A (para domínio raiz `marklaser.com.br`):
Crie 4 entradas do tipo `A` apontando para os IPs oficiais do GitHub Pages:
* `185.199.108.153`
* `185.199.109.153`
* `185.199.110.153`
* `185.199.111.153`

---

## 📊 Google Tag Manager (GTM)
O script do GTM está instalado no cabeçalho `<head>` de todas as páginas:
* **Container ID:** `GTM-WRHD6VFR`

---

## 🎨 Identidade Visual & Assets
* **Cores Principais:** Dark Ink (`#101820`), Azul Mark Laser (`#0757c8`), Ciano (`#42c4d9`).
* **Favicons:** Ícone vetorial da letra "M" em alta definição (`32x32`, `64x64`, `180x180`, `192x192`).
* **WhatsApp Comercial:** `+55 (21) 96409-2257`.
