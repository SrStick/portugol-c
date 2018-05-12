# Portugol-c

O projeto consiste na criação de um software em __Linguagem C__ capaz de converter um algoritmo codificado em __Portugol-C__ (portugol adaptado de acordo com as características da Linguagem C) para a linguagem C. Após a conversão o código é compilado e executado pelo próprio software.

## Pré-requisitos

O presente projeto é um programa em linguagem C que deve ser baixado e compilado na própria máquina. Além disso, o código resultante da tradução do portugol-c também resulta em um fonte em linguagem C. Por isto o pré-requisito inicial é que o sistema operacional possua o __GCC__ instalado e configurado para sua utilizaço no terminal.

Para instalar o __GCC__ abra o teminal do Linux (<b>CTRL+ALT+T</b>).
Em seguida digite:<br/>
<code>sudo apt-get install gcc</code>

## Instalação

 - Digite o seguinte comando no terminal:<br/>
   <code>$ wget https://raw.githubusercontent.com/flavio7co/portugol-c/master/instala-ptgc</code><br/>
   (isto fará download do script de instalação).<br/>
   
 - Para executar o script digite:<br/>
   <code>$ . instala-ptgc</code>
   <br/>
  <b>Observação:</b> O ponto garante que o script o levará para o diretório do ptgc onde estará o arquivo algoritmo.alg e elimina a necessidade de dar permissão de execução ao script).<br/>

Agora basta editar o arquivo algoritmo.alg, salvar e executar utilizando ./compila (pelo terminal, dentro do diretório do programa).
