# Relatório de Inspeção de Usabilidade

## Heurísticas de Nielsen

- H1. Visibilidade do Status do Sistema
- H2. Compatibilidade entre o sistema e o mundo real
- H3. Controle e liberdade para o usuário
- H4. Consistência e Padronização
- H5. Prevenção de erros
- H6. Reconhecimento em vez de memorização
- H7. Flexibilidade e eficiência de uso
- H8. Estética e design minimalista
- H9. Ajude os usuários a reconhecerem, diagnosticarem e recuperarem-se de erros
- H10. Ajuda e documentação

## Detecção de Defeitos

#### H8. Estética e design minimalista
- Na tela de login, a cor escolhida para informar os campos de “e-mail”, “senha” e “esqueceu senha” dificultam a visualização (leitura) dos mesmos. O fundo branco presente na maioria das telas torna a visualização das informações das telas bastante dificultosa.
- Na barra de pesquisa presente nas telas, a visualização da informação fornecida é dificultosa por conta da cor mais o fundo branco.
- No pop-up de tutorial fornecido para ajudar o usuário a utilizar o app, o fundo onde as informações das funcionalidades são descritas é transparente, causando confusão entre as informações fornecidas pelo tutorial e as informações das telas de fundo.
- O botão "Esqueceu a senha" não deve estar presente na tela "Cadastre-se", pois os usuários ainda não têm senhas para esquecer, já que estão em processo de cadastro.

#### H3. Controle e liberdade para o usuário
- Nas telas do tutorial, há a ausência da liberdade do usuário voltar a telas de informações anteriores. Assim que ele passa para a próxima informação, não tem como rever a informação anterior caso tenha alguma dúvida. E nas telas onde aparece a opção de voltar, quando clica para voltar, não funciona, restando somente a opção de passar para a seguinte informação.
- Quando o usuário acessa uma área nova, não tem opção para voltar. Caso queira voltar a uma área vista anteriormente, terá que fazer essa alteração por meio das abas principais.
- Para acessar o “Fórum”, “Blog”, “Aprenda” e o “Perfil” do usuário, é necessário primeiramente voltar à área de “Explorar” (isso a cada vez que o usuário quiser acessar uma opção de área diferente), dificultando a usabilidade. Não é possível acessar as áreas livremente independente de onde o usuário se encontre no momento.

#### H5. Prevenção de erros
- Na tela de login, não tem a opção de visualizar senha. Também não tem descrição do formato de como o usuário deve criar sua senha (ex: somente números, somente letras, inclusão de símbolos ou não).

#### H10. Ajuda e documentação
- O usuário não possui um botão de ajuda disponível dentro do aplicativo.

## Observações

#### Tela Fórum
- **Correção:** Corrigir “discurssão” para “discussão”
- **Melhoria no texto:** Refinar o texto para torná-lo mais formal e claro.

#### Tela Blog
- **Correção:** Alterar "aonde" para "onde".
- **Melhoria no texto:** Substituir "manja bem" por algo mais formal, como "entende bem".

#### Tela Aprenda
- **Correções:** "Esolha" para "Escolha", "sessão" para "seção", "haverão" para "apresentará".
- **Melhoria no texto:** Usar uma linguagem mais formal e técnica.

#### Melhorias na Navegação
- Garanta que o menu de navegação permita ir diretamente de qualquer tela (Fórum, Blog, Aprenda, Perfil) para outra tela, sem ter que passar pela tela Explorar.

# Tabelas


| **Heurísticas Violadas** | **Descrição do Problema**                                                                                                                                       | **Severidade** |
|:------------------------:|-------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------:|
| H3                       | Nas telas do tutorial, há a ausência da liberdade do usuário voltar a telas de informações anteriores. Assim que ele passa para a próxima informação, não tem como rever a informação anterior caso tenha alguma dúvida. | 04            |
| H3                       | Nas telas do tutorial onde aparece a opção de voltar, quando clica para voltar, não funciona, restando somente a opção de passar para a seguinte informação. | 04            |
| H3                       | Quando o usuário acessar uma área nova, não tem opção para voltar. Caso queira voltar a uma área vista anteriormente, terá que fazer essa alteração por meio das abas principais. | 04            |
| H3                       | Para acessar o “Fórum”, “Blog”, “Aprenda” e o “Perfil” do usuário, é necessário primeiramente voltar à área de “Explorar” (isso a cada vez que o usuário quiser acessar uma opção de área diferente), dificultando a usabilidade. Não é possível acessar as áreas livremente independente de onde o usuário se encontre no momento. | 04            |
| H5                       | Na tela de login, não tem a opção de visualizar senha. Também não tem descrição do formato de como o usuário deve criar sua senha (ex: somente números, somente letras, inclusão de símbolos ou não). | 03            |
| H8                       | Na tela de login, a cor escolhida para informar os campos de “e-mail”, “senha” e “esqueceu senha” dificultam a visualização (leitura) dos mesmos. O fundo branco presente na maioria das telas torna a visualização das informações das telas bastante dificultosa. | 03            |
| H8                       | Na barra de pesquisa presente nas telas, a visualização da informação fornecida é dificultosa por conta da cor mais o fundo branco. | 01            |
| H8                       | No pop-up de tutorial fornecido para ajudar o usuário a utilizar o app, o fundo onde as informações das funcionalidades são descritas é transparente, assim causando confusão entre as informações fornecidas pelo tutorial e as informações das telas de fundo. | 02            |
| H8                       | O botão "Esqueceu a senha" não deve estar presente na tela "Cadastre-se", pois os usuários ainda não têm senhas para esquecer, já que estão em processo de cadastro. | 02            |
| H10                      | O usuário não possui um botão de ajuda disponível dentro do aplicativo. | 02            |

#### Tabelas de Heurísticas Encontradas

| **ID** | **Descrição**                      | 
|:------:|:----------------------------------:|
| H3     | Controle e Liberdade do Usuário    |
| H5     | Prevenção de Erros                 |
| H8     | Estética e Design Minimalista      |
| H10    | Ajuda e Documentação               |

#### Classificação de Severidade

| **Grau** | **Descrição**      |
|:--------:|:------------------:|
| 0        | Não há problemas   |
| 1        | Cosmético          |
| 2        | Pequeno            |
| 3        | Grande             |
| 4        | Catastrófico       |
