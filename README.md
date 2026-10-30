# NeonAV Secure PRO ULTRA 🛡️

O **NeonAV Secure PRO ULTRA** é um scanner heurístico de arquivos **100% Client-Side** (roda inteiramente no navegador), desenvolvido para análise estática rápida, detecção de indicadores de comprometimento (IOCs), cálculo de entropia de bytes e hash criptográfico de arquivos suspeitos, sem enviar dados para servidores externos.

---

## 🚀 Principais Funcionalidades

* **Análise Heurística Avançada:** Varre o conteúdo do arquivo em busca de padrões associados a *Keyloggers*, *Info Stealers*, códigos ofuscados, comandos de terminal suspeitos (`powershell`, `cmd`, `/bin/bash`), persistência e credenciais expostas.
* **Cálculo de Entropia de Bytes:** Mede a densidade de informação dos arquivos para identificar possíveis conteúdos compactados, empacotados ou criptografados.
* **Geração de Hash SHA-512:** Utiliza a API nativa do navegador (`crypto.subtle`) para calcular assinaturas criptográficas robustas de forma otimizada.
* **Detecção Automática de IOCs:** Extrai e categoriza URLs, endereços IPv4, domínios e e-mails presentes nos arquivos analisados.
* **Laboratório de Testes Integrado:** Inclui um painel simulado com arquivos de teste (limpo, JavaScript suspeito, Stealer, PowerShell e crítico) para validar o comportamento das regras heurísticas em tempo real.
* **Armazenamento Local:** Salva o histórico de análises no `localStorage` do navegador para consulta posterior.
* **Exportação de Relatórios:** Permite exportar os resultados e históricos completos nos formatos **JSON**, **CSV** e **HTML**.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3:** Interface responsiva com design moderno em modo escuro (*Dark Mode*) e animações suaves.
* **JavaScript (ES6+ puro):** Sem dependências externas ou frameworks pesados, garantindo máxima performance e privacidade.
* **Web APIs:** `Crypto API` (SHA-512), `File API`, `Blob API` e `Clipboard API`.

---

## 📦 Como Usar

1. **Baixe ou salve** o código em um arquivo local (por exemplo, `index.html`).
2. **Abra o arquivo** diretamente em qualquer navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.).
3. Na tela de boas-vindas (*Capa*):
* Clique em **🚀 Acessar Sistema** para ir direto à área de análise.
* Ou clique em **🧪 Abrir Laboratório de Testes** para gerar arquivos simulados e testar as detecções imediatamente.


4. **Para analisar seus próprios arquivos:**
* Arraste e solte os arquivos na **Área de Análise** ou clique em **Selecionar arquivos**.
* Clique no botão **🛡️ Iniciar análise**.


5. Utilize os filtros de busca e risco na seção de resultados para gerenciar os arquivos processados, ou utilize os botões de exportação para gerar relatórios detalhados.

---

## ⚙️ Configurações Disponíveis

No painel lateral de configurações, você pode habilitar ou desabilitar opcionalmente:

* **Detecção de URLs** e links suspeitos.
* **Análise de Entropia** de bytes.
* **Detecção de extensões perigosas/executáveis** (`.exe`, `.bat`, `.ps1`, `.scr`, etc.).
* **Detecção de IOCs**.
* **Limite de tamanho por arquivo** (opções de 5 MB, 10 MB, 25 MB ou 50 MB).

---

## 🔒 Privacidade e Segurança

Como toda a execução ocorre localmente no navegador do usuário, **nenhum arquivo enviado para o NeonAV é transmitido para servidores remotos**, garantindo total privacidade e confidencialidade dos dados analisados.

---

*Desenvolvido para fins educacionais, de auditoria defensiva e análise preliminar.*
