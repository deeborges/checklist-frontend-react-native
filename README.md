**Checklist para tasks de front end**

* Analisar qual foi o real objetivo da tarefa!
* Testar a tarefa em 3 dispositivos diferentes (pequeno, médio e grande).
  * Em cada dispositivo, verificar os seguintes pontos
    * Como as fontes estão se comportando?
     * Trabalhar nessa tarefa, com pixel, está funcionando normalmente em todos os dispositivos testados?
     * Trabalhar nessa tarefa, pegando a dimensão do dispositivo e adpatando o tamanho da fonte, está funcionando normalmente em todos os dispositivos testados?
     * A fonte definida é a mesma que a do mockup?
     * Propriedades como **fontWeight** não estão "quebrando" ou "alterando a fisionomia" da fonte?
     * A cor definida é a mesma que a do mockup?
     * A fonte definida é a mesma que a do mockup, mas por um acaso há uma inconsistência na tipografia? 
        (exemplo: uma letra diferente, uma letra sem acento e afins...)
          * Tudo ok? Que tal testar agora no iOS?

  * E o sombreamento dos cards?
    * A propriedade **boxShadow** está sendo aplicada de forma correta no **Android** e no **iOS**
      (se houver dúvida, consulte: https://ethercreative.github.io/react-native-shadow-generator/)

  * E os alinhamentos?
    * verificar o uso do space-between e space-around
      * o Around por sua vez, adiciona um preenchimento que, pra dispositivos grandes fica legal, mas em dispositivos pequenos fica meio que com o layout achatado (podendo fugir da ideia do mockup).
      * Já o Between, necessita que o padding seja setado manualmente (em dispositivos grande pode ficar meio esquisito), ja nos menores... fica bem de boas
      * A ideia aqui é testar e definir o melhor alinhamento possível para que, em ambos os dispositivos, o layout seja fiel ao mockup.
