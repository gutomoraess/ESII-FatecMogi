# ANOTAÇÕES DIA 13-03-2023
- Diagrama de casos de uso  
    - Atores: Alguém ou alguma coisa que interage com o sistema.
    - Caso de uso: conjunto importante de ações que o seu sistema executa.  
    <img src="https://www.macoratti.net/netuml21.gif"><br>
    O ator interage com o caso de uso.  
    Exemplo da internet:  
    <img src="https://i.stack.imgur.com/0pzVS.png"><br>
    Exemplo Luque:  
    <img src="https://i.imgur.com/uFoMkBS.png"><br>
    &lt;include&gt; e &lt;extend&gt;  
    Generalização (triângulo na ponta) -> relacionamento entre atores ou entre casos de usos

    - Include:  
    Quando o caso de uso A “inclui” o caso de uso B, significa que sempre que o caso de uso A for executado o caso de uso B também será executado. A direção do relacionamento é do caso de uso que está incluindo para o caso de uso incluído.

    - Extend:  
    Quando o caso de uso B estende o caso de uso A, significa que quando o caso de uso A for executado o caso de uso B poderá (poderá – talvez não seja) ser executado também. A direção do relacionamento é do caso de uso extensor (aqui o caso de uso B) para o caso de uso estendido (aqui o caso de uso A).

    - Generalization:  
    Quando o caso de uso B generaliza o caso de uso C isso significa que, além de fazer tudo que nele está especificado (ele = B), ele também executará tudo que está especificado no caso de uso C.
    A direção do relacionamento é sempre do generalizador (aqui o caso de uso B) para o generalizado (caso de uso C).

    - [Fonte](https://www.ateomomento.com.br/caso-de-uso-include-extend-e-generalizacao/)