# Anexo C (normativo): Determinação de conformidade

## C.1 Introdução

Este anexo normativo estabelece os meios necessários para determinar o cumprimento dos
requisitos individuais estabelecidos no corpo do presente documento. Todas as cláusulas,
exceto a 12, são de auto-análise. Isto significa que são introduzidas com a frase 'Onde a
TIC <pré-condição>'. A conformidade é verificada quando a pré-condição é verdadeira e o
teste correspondente (no Anexo C) é positivo, ou quando a pré-condição é falsa (ou seja, a
pré-condição não é atendida ou não é válida).

Para apoio ao leitor, foram inseridas algumas cláusulas vazias para que a numeração do
anexo reflita a numeração das cláusulas dos requisitos.

As TIC são frequentemente compostas por dois ou mais itens de TIC. Em alguns casos, dois
ou mais itens interoperáveis da TIC podem, conjuntamente, cumprir mais requisitos da norma
quando um item complementa a funcionalidade do outro e a soma do conjunto satisfaz
requisitos de acessibilidade. No entanto, a combinação de dois itens de TIC que
cumprem nenhum requisito específico, não levará a um sistema combinado de TIC que
atenda a esse requisito. 

O presente documento não prioriza os requisitos. A priorização desses requisitos é deixada 
ao critério do utilizador do presente documento. 

A priorização dos requisitos que se alinham com o contexto de utilização pode melhorar 
a acessibilidade, no caso de conformidade parcial, e a justificação para essa priorização, 
se usada, deve ser declarada. 

A conformidade deve ser reportada num formulário tal que: 

- seja claro se há conformidade com todos os requisitos aplicáveis ou se há conformidade apenas com alguns requisitos; 
- sejam registadas as técnicas de amostragem e avaliação utilizadas para avaliar as TIC; 
- se anote se a funcionalidade acessível equivalente existe em locais onde a não-conformidade tenha sido
encontrada; e 
- se observa se foram utilizados meios equivalentes que atingem o resultado previsto, quando a não-conformidade técnica tenha sido encontrada.

NOTA 1: Em algumas situações, quando este documento é usado para outros fins que não
a Diretiva 2016/2102 [i.28], as necessidades de acessibilidade do utilizador podem ser
atendidas por um subconjunto de requisitos. Por exemplo, onde as TICs são desenvolvidas
para serem usadas por um utilizador específico, ou num cenário de utilização bem definido,
uma declaração de desempenho funcional particular na cláusula 4.2 e/ou requisito
associado das cláusulas 5 a 13, poderia ser omitida, caso essa omissão não tenha impacto
negativo nas necessidades de acessibilidade dos utilizadores previstos originalmente. <br> NOTA
2: A conformidade com os requisitos de acessibilidade pode ser afetada pela implementação
ou manutenção subsequente.<br> NOTA 3: A amostragem é frequentemente necessária em TICs
complexas, quando há muitas instâncias do objeto a ser testado. Este documento não
pode recomendar técnicas específicas de avaliação por amostragem, pois estas são
particulares de cada contexto.

## C.2 Cláusula vazia

Esta cláusula está intencionalmente vazia.

## C.3 Cláusula vazia

Esta cláusula está intencionalmente vazia.

## C.4 Desempenho funcional

A Cláusula 4 é informativa e não contém requisitos que precisem de testes.

## C.5 Requisitos gerais

### C.5.1 Funcionalidade fechada

#### C.5.1.1 Introdução

A Cláusula 5.1.1 é informativa e não contém requisitos que precisem de testes.

#### C.5.1.2 Geral

##### C.5.1.2.1 Funcionalidade fechada

As TIC com funcionalidade fechada devem cumprir os requisitos nas cláusulas C.5.2 a C.13, como aplicável.

##### C.5.1.2.2 Tecnologia de Apoio

 Tipo de avaliação  |Teste
--------------------|-----------------------------------------
 Pré-condições      | 1. A TIC tem funcionalidade fechada.    
 Procedimento       | 1. Determine as funções fechadas da TIC.<br>2. Verifica-se que os testes C.5.1.3 a C.5.1.6 podem ser feitos sem a utilização de qualquer tecnologia de apoio, com exceção de headsets ou inductive loops. 
 Resultado           | Passa: A verificação 2 é verdadeira<br>Falha: A verificação 2 é falsa

#### C.5.1.3 Acesso não visual

##### C.5.1.3.1 Geral

Tipo de avaliação       | Teste
------------------------|-------
Pré-condições           | 1. É necessária informação visual para ativar as funções da TIC que são fechadas a tecnologias de apoio para leitura de ecrã.
Procedimento            | 1. Determinar as funções da TIC que são fechadas a leitor de ecrã.<br>2. Verifica-se que as funções identificadas são operáveis com acesso não visual.
Resultado               | Passa: A verificação 2 é verdadeira<br>Falha: A verificação 2 é falsa

##### C.5.1.3.2 Retorno auditivo incluindo fala

Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. É fornecida um retorno auditivo como acesso não visual à funcionalidade fechada.
Procedimento     |1. Verificar que o retorno auditivo é fornecida por um mecanismo incluido ou fornecido com a TIC.<br>2. Verifica-se que o retorno auditivo é fornecida por um auscultador pessoal que pode ser ligado através de um audio jack de 3,5 mm ou uma ligação standard da indústria tal que não seja necessário acesso visual.
Resultado        |Passa: A verificação 2 é verdadeira<br>Falha: A verificação 2 é falsa

##### C.5.1.3.3 Correlação do retorno auditivo

A Cláusula 5.1.3.3 é apenas informativa e não contém requisitos que precisem de testes.

##### C.5.1.3.4 Controlo através da fala

Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. A fala é fornecida como um acesso não-visual à funcionalidade fechada.
Procedimento     |1. Verificar que a fala pode ser interrompida quando requerido pelo utilizador.<br>2. Verificar que a fala pode ser repetida quando requerido pelo utilizador.
Resultado        |Passa: Todas as verificações são verdadeiras<br>Falha: Pelo menos uma das verificações é falsa.

##### C.5.1.3.5 Interrupção automática da fala

Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. A Fala é fornecida como um acesso não-visual à funcionalidade fechada.
Procedimento     |1. Determinar as funcionalidades fechadas da TIC.<br>2. Verificar que a saída de fala para cada função é interrompida por ação do utilizador.<br>3. Verificar que a saída de fala para cada função é interrompida quando uma nova saída de fala é iniciada.
Resultado        |Passa: As verificações 1 e 3 são verdadeiras. são verdadeiras<br>Falha: As verificações 1 e 3 são falsas.

##### C.5.1.3.6 Fala para conteúdo não-textual

Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. A Fala é fornecida como um acesso não-visual à funcionalidade fechada.
Procedimento     |1. Determinar as funcionalidades fechadas da TIC.<br>2. Verificar que texto não é apenas decorativo.<br>3. Verificar que o texto não é usado apenas para formatação visual.<br>4. Verificar que a saída de fala segue orientação da "alternativa de texto" descrita no Critério de Sucesso 1.1.1 da WCAG 2.1.
Resultado        |Passa: Todas as verificações são verdadeiras; ou 1 e 2 são falsas; ou 1 e 3 são falsas.<br>Falha: Verificação 1 é verdadeira e 2 é falsa; 1 é verdadeira e 3 é falsa; ou 1 e 2 e 3 são verdadeiras e 4 é falsa .

##### C.5.1.3.7 Fala para informação em vídeo

Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. É necessário conteúdo de vídeo pré-gravado para ativar a utilização de funcionalidades fechadas da TIC.<br>2. A saída de fala é fornecida como acesso não-visual a conteúdo não-textual exibido na funcionalidade fechada.
Procedimento     |1. Verificar que a saída de fala apresenta informação equivalente à do conteúdo pré-gravado do vídeo.
Resultado        |Passa: A verificação 1 é verdadeira<br>Falha: A verificação 1 é falsa.

##### C.5.1.3.8 _Masked entry_

Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. O retorno auditivo é fornecido como acesso não-visual à funcionalidade fechada.
<br>2. Os caracteres exibidos são masking characters***.
<br>3. O utilizador não escolhe especificamente permitir saída auditiva não-privada.
Procedimento     |1. Verificar que a saída auditiva não é uma versão falada dos carateres escritos.
<br>2. Verificar que é conhecido que a saída auditiva é fornecida apenas para um mecanismo de escuta privada.
<br>3. Se 1 e 2 são falsos, verificar que o utilizador escolheu específicamente permitir a saída auditiva não-privada.
Resultado        |Passa: Pelo menos uma das verificações é verdadeira.<br>Falha: Todas as verificações são falsas.

##### C.5.1.3.9 Acesso privado a dados pessoais

Tipo de avaliação|Teste
-----------------|-------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.
<br>2. A saída contém dados.
<br>3. Aplica-se uma política de privacidade de dados que considera os dados privados.
Procedimento     |1. Verificar que a saída auditiva é fornecida apenas para um mecanismo de escuta privada.
<br>2. Verificar que o mecanismo de escuta privada pode ser ligado sem precisar da visão.
<br>3. Verificar que a saída auditiva pode ser fornecida por qualquer outro mecanismo escolhido pelo utilizador.
Resultado        |Passa: A verificação 1 ou 2 são verdadeiras; ou 3 é verdadeira.<br>Falha: As verificações 1 ou 2 e 3 são falsas.

##### C.5.1.3.10 Saída de áudio sem interferência

Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.
2. A TIC reproduz automaticamente saída de áudio com interferência.
Procedimento     |1. Verificar que a interferência audível não dura mais de 3 segundos.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.5.1.3.11 Volume de escuta privada

Tipo de avaliação|Inspeção
-----------------|-------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.
<br>2. A saída auditiva é fornecida por um mecanismo de escuta privada.
Procedimento     |1. Verificar que existe pelo menos um modo de operação não-visual para controlar o volume do som.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.1.3.12 Volume do altifalante

Tipo de avaliação|Inspeção e Medida
-----------------|-----------------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.
<br>2. A saída auditiva é fornecida por altifalantes.
Procedimento     |1. Verificar que existe um modo de operação não-visual para controlar incrementalmente o volume do som.
<br>2. Verificar que a amplificação pode ir o nível, de pelo menos, 65 dBA (-29 dBPaA).
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: As verificações 1 e/ou 2 são falsas.

#### C.5.1.3.13 Reinicialização do volume

Tipo de avaliação|Inspeção e Medida
-----------------|-----------------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.
<br>2. A saída auditiva não é dedicada a apenas um utilizador.
Procedimento     |1. Verificar que existe um modo de automaticamente colocar o som a 65 dBA, ou menos, depois de cada utilização.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.1.3.14 Idiomas falados

Tipo de avaliação|Teste
-----------------|-----------------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.
<br>2. A saída de fala não é nomes próprios, termos técnicos, palavras de idioma indeterminado, e palavras ou frases que fazem parte do vernáculo do texto circundante.
<br>3. **O conteúdo não é gerado externamente e está sob controlo do vendedor da TIC.
<br>4. Os idiomas exibidos podem ser selecionados usando acesso não-visual.
<br>5. O utilizador não selecionou um idioma de saída de fala diferente do idioma do conteúdo exibido.
Procedimento     |1. Verificar que o idioma da saída de fala é o mesmo do conteúdo exibido.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.5.1.3.15 Identificação não-visual de erro

Tipo de avaliação|Teste
-----------------|-----------------
Pré-condições    |1. A saída auditiva é fornecida como acesso não-visual à funcionalidade fechada.
<br>2. Um erro de entrada é automaticamente detetado.
Procedimento     |1. Verificar que o idioma da saída de fala identifica o elemento que está com erro.
<br>1. Verificar que o idioma da saída de fala descreve o elemento que está com erro.
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: As verificações 1 e/ou 2 são falsas.

##### C.5.1.3.16 Recibos, bilhetes e saídas transacionáveis

Tipo de avaliação|Teste
-----------------|-----------------
Pré-condições    |1. A TIC é fechada ao acesso visual. 
<br>2. A TIC fornece recibos, bilhetes, ou outras saídas como um resultado de uma transação self-service.
<br>3. A informação verificada não se trata de cópias impressas de itinerários e mapas.
Procedimento     |1. Verificar que a saída de fala é fornecida, incluindo toda a informação necessária para completar ou verificar a transação.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.1.4 Funcionalidade fechada à ampliação de texto

Tipo de avaliação|Inspeção e Medida
-----------------|-----------------
Pré-condições    |1. A funcionalidade da TIC é fechada a características de ampliação da plataforma ou tecnologia de apoio.
<br>2. Uma distância de visualização é especificada pelo fornecedor.
Procedimento     |1. Medir a altura da letra maiúscula H.
<br>2. Verificar que subtende um ângulo de, pelo menos, 0,7 graus da visualização especificada.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.1.5 Retorno visual para informação auditiva

Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A informação auditória pré-gravada é necessária para permitir o uso de funcionalidades fechadas da TIC.
Procedimento     |1. Verificar que a informação visual é equivalente à saída auditiva pré-gravada.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.1.6 Operação sem interface de teclado

##### C.5.1.6.1 Funcionalidade fechada

Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é fechada a teclados e interfaces de teclado. 
Procedimento     |1. Verificar que todas as funcionalidades são operáveis sem visão.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

##### C.5.1.6.2 Foco de Entrada

Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC é fechada a teclados e interfaces de teclado. 
<br>2. O foco de entrada pode ser movido para um elemento de interface de utilizador.
Procedimento     |1. Verificar que é possível mover o foco de entrada desse elemento para outro usando o mesmo mecanismo.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.2 Ativação dos recursos de acessibilidade

Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem características de acessibilidade documentadas para cumprir uma determinada necessidade.
Procedimento     |1. Verificar que é possível ativar essas características de acessibilidade sem precisar de um método que não suporta essa necessidade. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.3 Biometria

Tipo de avaliação|Teste 1
-----------------|--------
Pré-condições    |1. A TIC usa características biológicas para identificação de utilizador.
Procedimento     |1. Verificar que mais do que um meio pode ser usado para identificação de utilizador. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

Tipo de avaliação|Teste 2
-----------------|--------
Pré-condições    |1. A TIC usa características biológicas para controlo da TIC.
Procedimento     |1. Verificar que mais do que um meio pode ser usado para controlar a TIC. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.4 Preservação da informação de acessibilidade durante a conversação

Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A informação não-proprietária fornecida para acessibilidade é documentada.
<br>2. A TIC converte informação ou comunicação.
<br>3. A informação não-proprietária fornecida para acessibilidade pode ser contida no formato de destino. 
<br>4. A informação não-proprietária fornecida para acessibilidade pode ser suportada pelo formato de destino. 
Procedimento     |1. Verificar que informação não-proprietária fornecida para acessibilidade é preservada quando a TIC converte informação ou comunicação. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.5 Partes operáveis

#### C.5.5.1 Modos de operação

Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. A TIC tem partes operáveis que requerem agarrar, prensar ou torcer o pulso para operar.  
Procedimento     |1. Verificar que há modos de operação alternativos acessíveis que não requerem estas ações. 
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

#### C.5.5.2 Perceção das partes operáveis

Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. A TIC tem partes operáveis.  
Procedimento     |1. Identificar que há um modo de discernir cada parte operável sem a visão. 
<br>2. Verificar que a ação associada com a parte operável não foi executada quando a usar o modo de discernir cada parte operável, no passo 1.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.6 Controlos de bloqueio ou alternância

#### C.5.6.1 Estado tátil ou auditivo

Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem um controlo de bloqueio ou de alternância.
<br>2. O controlo de bloqueio ou de alternância é visualmente apresentado ao utilizador.
Procedimento     |1. Verificar que pelo menos um modo de operação onde o estado de todos os controlos de bloqueio ou alternância pode ser determinado por toque sem operar o controlo. 
<br> 2. Verificar que há pelo menos um modo de operação onde o estado de todos os controlos de bloqueio ou alternância pode ser determinado por som sem operar o controlo.  
Resultado        |Passa: A verificação 1 ou a 2 é verdadeira.<br>Falha: As verificações 1 e 2 são falsas.

#### C.5.6.2 Estado visual

Tipo de avaliação|Inspeção
-----------------|--------
Pré-condições    |1. A TIC tem um controlo de bloqueio ou de alternância.
<br>2. O controlo de bloqueio ou de alternância é apresentado ao utilizador.
Procedimento     |1. Verificar que há pelo menos um modo de operação onde o estado de todos os controlos de bloqueio ou alternância pode ser visualmente determinado quando o controlo é apresentado.
Resultado        |Passa: A verificação 1 é verdadeira.<br>Falha: A verificação 1 é falsa.

### C.5.7 Repetição de Tecla

Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. A TIC tem uma função de repetição de tecla. Um teclado com repetição de tecla é fornecido. 
<br>2. A repetição de tecla não pode ser desligada.  
Procedimento     |1. Verifique que o tempo entre repetições pode ser ajustado para, pelo menos, 2 segundos.  
<br>1. Verifique que o tempo entre repetições de uma mesma tecla pode ser ajustado para, pelo menos, 2 segundos. 
Resultado        |Passa: As verificações 1 e 2 são verdadeiras.<br>Falha: As verificações 1 e 2 são falsas.

### C.5.8 Ativação dupla de tecla

Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |1. A TIC tem um teclado. Um teclado é fornecido. 
Procedimento     |1. Verifique que há um mecanismo de ajuste do tempo durante o qual, após uma tecla ser pressionada, são ignoradas pressões dessa mesma tecla.  
<br>2. Ajuste o mecanismo para o seu valor máximo.
<br>3. Prima qualquer tecla. 
<br>4. Depois de 0,5 segundos, prima a mesma tecla que foi premida no passo 3.
<br>5. Verifique se a tecla premida no passo 4 foi aceite.  
Resultado        |Passa: A verificação 1 é verdadeira e a 5 é falsa.<br>Falha: A verificação 1 é falsa e a 5 é verdadeira.

### C.5.9 Ações simultâneas do utilizador

Tipo de avaliação|Teste
-----------------|--------
Pré-condições    |Nenhuma  
Procedimento     |1. Se houver múltiplos modos de operação, selecione um modo de operação (ver notas 1 e 2 desta tabela para orientação na seleção). 
<br>2. Determinar todas as funções controláveis pelo utilizador.
<br>3. Verificar que cada função pode ser controlada com apenas um ponto de contacto. 
<br>4. Se houver múltiplos modos de operação e o teste não tiver passado, repita o procedimento até que todos os modos tenham sido testados. 
Resultado        |Passa: A verificação 3 é verdadeira.<br>Falha: A verificação 3 é falsa para todos os modos de operação.

