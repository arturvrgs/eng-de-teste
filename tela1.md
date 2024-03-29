## 1. Introdução
- **Nome do projeto:** E-DUQ - Tela 1/3
- **Versão do software:** 0.0.8
- **Data do teste:** 21/02/24
- **Testadores:** Artur Vargas
- **Objetivo do teste:** Validação de informações dos campos de registro para o cadastro de administrador.

## 2. Escopo do Teste
- **Funcionalidades testadas:** Inputs de <i>Nome, Sobrenome, Email, Senha, Data de Nascimento, Telefone, RG e CPF</i>
- **Navegadores e dispositivos testados:** Firefox, Chrome
- **Ambiente de teste:** Selenium IDE

## 3. Resumo dos Resultados
- **Número de testes realizados:** 1
- **Número de testes com falha:** 0
- **Número de bugs encontrados:** 0
- **Gravidade dos bugs encontrados:** Nenhuma

## 4. Detalhes dos Testes
- **Teste 1:**
  - **Descrição do teste:** Validação de informações colocadas nos campos de registro
  - **Resultado esperado:** Registrar usuário com sucesso
  - **Resultado obtido:** Usuário registrado
  - **Status (passou/falhou):** Passou
    - **Evidências (capturas de tela, logs, etc.):**
       <img height="300px" style="border-radius: 10px;" src="assets/teste1.png"/>
  - **Observações:** O bom resultado dos testes acontecem devido a colocação de atributos nas tags HTML onde evitam erros.
  
   Por exemplo: 
  ```
    <input type="password"/> 
  ```

## 5. Conclusões
- **Resumo dos resultados do teste:** Sucesso no cadastro do usuário
- **Recomendações para correções de bugs:** Não houve bugs
- **Riscos e problemas identificados:** Aceitar somente o tipo texto nos campos <i>Nome e Sobrenome</i> e verificação de idade mínima com o campo <i>Data</i> 
- **Próximos passos:** Adicionar atributos HTML para resolver os riscos.

## <a href="tela2.md">TELA 02</a>

<!-- ## 6. Apêndices
- **Lista completa de bugs encontrados:** Não houve bugs
- **Logs de teste:** [Inserir logs de teste]
- **Capturas de tela e outras evidências:** [Inserir capturas de tela e outras evidências]
- **Observações:** [Inserir observações adicionais] -->
