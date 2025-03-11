# 🎁 Entregável Parcial 1 (EP1) - Protótipo de Alta Fidelidade

| 🖼️ Logo | 🖌️ Processo Criativo | 🎨 Paleta de Cores | 🔤 Fonte |
|---------|------------------|---------|-------------|
|![logo-jifa](https://github.com/jifa-team/ep1-pi3/blob/main/logo-jifa.png) | A logo trás um design minimalista e moderno. O ícone de um dente estilizado simboliza cuidado e saúde bucal, enquanto a tipografia transmite profissionalismo e confiança.  | 🔹 `#FFFFFF` _100%_ <br> 🔸 `#6C757D` <br>⚪ `#FFFFFF` _80%_ <br>⚫ `#717275`   | **Montserrat**, Sans-serif |


# 🌐 As Páginas (Frame) criadas

*  🔐 `cliente/login` : Página de login para clientes acessarem o sistema.
*  ⚠️ `cliente/login/error` : Exibe mensagens de erro ao tentar fazer login.
*  📝 `cliente/cadastro` : Permite o cadastro de novos clientes na plataforma.
*  🏠 `cliente/home` : Página inicial com informações gerais da Jifa Odonto e demais destaques.
* 👥 `cliente/quem-somos` : Apresentação da clínica, sua equipe e missão.
* 🏥 `cliente/clinica` : Informações sobre a clínica e seus serviços.
* 🎛️ `cliente/painel-do-cliente` : Área restrita com funcionalidades para o cliente.
* 💳 `cliente/planos` : Página com opções de planos odontológicos disponíveis na Jifa Odonto.
* 📜 `cliente/planos/tipos-de-planos` : Detalhes sobre os diferentes tipos de planos oferecidos.
* 🛒 `cliente/planos/tipos-de-planos/aquisicao` : Processo de aquisição de um plano.

<img src="https://github.com/jifa-team/ep1-pi3/blob/main/layout.gif" width="50%"> 

# 🖌️ Padrões de Nomeação no Figma

## 🎯 Objetivo
Este documento define um padrão de nomenclatura para os elementos do Figma, facilitando a comunicação entre os participantes do projeto.

## 📑 Convenções Gerais
- Usamos **abreviações curtas** e intuitivas.
- Nomeamos elementos conforme suas funções, próximas a do HTML.
- Mantemos **nomes (abreviação) em inglês** para padronizar com código, seguido do objetivo daquela layer **em português**, podendo ter mais de um nome.
- Deixamos como exceção as layers Header e Footer que permaneceram com seus nomes sem abreviação.
Exemplo: `btn-localizacao`, **btn** para button (botão), **localização** como o próprio nome indica. 

Essa estrutura é um agrupamento (crtl + g, tecla atalho no figma para agrupar elementos) de três (3) layers, `ico-localizacao`, `txt-localizacao`, `bg-btn-localizacao`, ou seja, um botão, que é formado pelo agrupamento de elementos.

## 🤔 Para que tanto trabalho em renomear? 
**Resposta curta:** melhorar o entendimento.

**Resposta menos curta:** Melhora a organização, facilita a compreensão para novos membros da equipe e agiliza a entrega para desenvolvedores. Isso evita confusão, melhora a busca por elementos e mantém um padrão claro no projeto. 🚀

## Tabela comparativa do elementos do Figma da página `cliente/home` .

| Elemento Original                                      | Elemento Renomeado                  |
|----------------------------------------------|----------------------------|
| 🔤 Realize sua avaliação gratuita             | txt-avaliacao-gratuita     |
| #️⃣ Header                                   | Header                     |
| #️⃣ more_horiz_24dp_5F6368_FILL0_wght400_GRAD0_opsz24 1 | ico-tres-pontos          |
| #️⃣ arrow_forward_ios_24dp_5F6368_FILL0_wght400_GRAD0_opsz24 1 | ico-seta-direita        |
| #️⃣ arrow_back_ios_24dp_5F6368_FILL0_wght400_GRAD0_opsz24 1  | ico-seta-esquerda       |
| 🟦 Rectangle 64                              | img-post-3                 |
| 🟦 Rectangle 62                              | img-post-1                 |
| 🟦 Rectangle 63                              | img-post-2                 |
| 🔹 Panel Image Double                        | bg-sec-blog                |
| 🔤 Como posso agendar uma consulta na clínica?| txt-btn-faq2               |
| 🔤 A clínica aceita plano de saúde/convênio odontológico? | txt-btn-faq3  |
| 🔤 Quais são os principais serviços oferecidos pela clínica? | txt-btn-faq1  |
| 📍 location_on                               | ico-localizacao            |
| T Usar localização atual                     | txt-localizacao            |
| #️⃣ Group 1                                   | bg-btn-localizacao         |
| ⭐ Star 5                                    | ico-avaliacao-2            |
| ⭐ Star 6                                    | ico-avaliacao-3            |
| ⭐ Star 7                                    | ico-avaliacao-4            |
| ⭐ Star 8                                    | ico-avaliacao-1            |
| ⭐ Star 4                                    | ico-avaliacao-1            |
| T Blog                                       | txt-sec-blog               |
| T Perguntas frequentes                       | txt-sec-faq                |
| T Avalie o nosso atendimento e nos ajude a melhorar | txt-avaliacao    |
| T Avalie agora                               | btn-avaliacao              |
| 🔹 Panel Image                               | img-topo                   |
| 🔹 Input Field                               | txt-avaliacao-gratuita     |
| 🔹 Bottom app bar                            | btn-avaliacao              |
| 🔹 Bottom app bar                            | btn-2                      |
| 🔹 Bottom app bar                            | btn-3                      |
| 🔹 Bottom app bar                            | btn-1                      |
| 🟦 JIFA 1                                    | bg-jifa                    |
| 🟦 Footer                                   | Footer                   |

## Elementos agrupados e organizados.

#### #️⃣ Header (1)

#### 🔹 img-topo (2)

#### 🔤 txt-avaliacao-gratuita (3)

#### 📂 btn-localizacao (4)
   - 📍 ico-localizacao  (4.1)
   - 🔤 txt-localizacao  (4.2)
   - #️⃣ bg-btn-localizacao  (4.3)

#### 📂 sec-faq (5)
   - 🔤 txt-sec-faq  (5.1)
   - 📂 btn-faq1 (5.2)
     - 🔤 txt-btn-faq1 (5.2.1)
     - 🔹 btn1 (5.2.2)
   - 📂 btn-faq2 (5.3)
     - 🔤 txt-btn-faq2 (5.3.1)
     - 🔹 btn2 (5.3.2)
   - 📂 btn-faq3 (5.4)
     - 🔤 txt-btn-faq3 (5.4.1)
     - 🔹 btn3 (5.4.2)

#### 📂 sec-avaliacao (6)
   - 🔤 txt-avaliacao  (6.1)
   - 📂 ico-avaliacao-1 (6.2)
     - ⭐ ico-avaliacao-1  (6.2.1)
     - ⭐ ico-avaliacao-2 (6.2.2)
     - ⭐ ico-avaliacao-3 (6.2.3)
     - ⭐ ico-avaliacao-4 (6.2.4)
     - ⭐ ico-avaliacao-5 (6.2.5)            
   - 📂 btn-avaliacao (6.3)
     - 🔤 txt-btn-avaliacao (6.3.1)
     - 🟦 bg-btn-avaliacao (6.3.2)

#### 📂 sec-blog (7)
   - 🔤 txt-sec-blog (7.1)
   - 🟦 img-post-1 (7.2)
   - 🟦 img-post-2 (7.3)
   - 🟦 img-post-3 (7.4)
   - #️⃣ ico-seta-direita (7.5)
   - #️⃣ ico-seta-esquerda (7.6)
   - #️⃣ ico-tres-pontos (7.7)
   - #️⃣ bg-sec-blog (7.8)

#### 🟦 bg-figma (8)

#### #️⃣ Footer (9)     

## E agora mais visual.
![organizacao-visual](https://github.com/jifa-team/ep1-pi3/blob/main/elemetos-agrupados.svg)

### 🔹 Glossário para Padrão de Nomeação de Elementos no Figma
| Elemento | Nome no Figma |
|----------|--------------|
| Background | `bg` |
| Button | `btn` |
| Card | `card` |
| Checkbox | `chk` |
| Component | `cmp` |
| Field | `fld` |
| Footer | `Footer` |
| Form | `form` |
| Header | `Header` |
| Icon | `ico` |
| Image | `img` |
| Input | `inp` |
| Item | `item` |
| Link | `lnk` |
| Radio Button | `rdo` |
| Section | `sec` |
| Text | `txt` |

# ⚠️ Links Importantes.

- <a href="https://www.youtube.com/watch?v=FhBx-93DYS8" target="_blank">Apresentação Entregável da Sprint</a>
- <a href="https://www.figma.com/design/290aCDuakXyI3m3TFTVQhm/Jifa-Odonto?node-id=2013-774&p=f&t=jkw650Q5Tx71Sz1w-0" target="_blank">Projeto no Figma</a>







