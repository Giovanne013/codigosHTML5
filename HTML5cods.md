codigos em HTML
----------------------------------------------------------------------------------------------------
<h1> titulo principal
<h2>subtitulo
----------------------------------------------------------------------------------------------------
<p> texto
----------------------------------------------------------------------------------------------------
<div>  tag para dividir e organizar blocos por codigos  exemplo 



                    <div>

     <h1> olá, mundo!</h1>
     <p>meu  primeiro texto em HTML </p> 
     <p> separando as  Tags como div </p>

                    </div>

----------------------------------------------------------------------------------------------------




<a href="www.instagram.com"target=blank> ir para link</a>

     <a href=""></a> ( gerar um click link e direcionando para a pagina)


                            targt= blank( abrir outra aba do link colocado ) 


----------------------------------------------------------------------------------------------------


----------------------------------------------------------------------------------------------------
<img src="foto.arquivo.jpg" alt=" resumo em texto doq essa foto significa">     


             tag para adicionar uma imagem pelo ' copiar caminho da imagem' ou vc pode ter a imagem baixada em alguma pasta 
--------------------------------------------------------------------------------------------------------------------------------------


--------------------------------------------------------------------------------------------------------------------------------------
CSS
 
   h1 { font-family: Arial;
         font-size: 30;
        color: rgb(12, 151, 24);
        text-shadow:' tamanho pixel' px 3px  3px bqualquer cor ;}
--------------------------------------------------------------------------------------------------------------------------------------
TAG   </br>  para pular para a linha de baixo exemplo


   www.google.com.br link

   www.facebook.com  link              



       <a href="https://www.google.com/" target="_blank"> ir para o planeta c137</a>
    </br>
       <a href="https://www.facebook.com/"> ir para google </a>

--------------------------------------------------------------------------------------------------------------------------------------

   <!-- comentario visivel para  todos no site apenas na parte de inspecionar --!>

--------------------------------------------------------------------------------------------------------------------------------------

<hr/>   é uma tag de quebra de linhas   

--------------------------------------------------------------------------------------------------------------------------------------



--------------------------------------------------------------------------------------------------------------------------------------

  tag de listas uma embaixo da outra de itens que tenham ordem para ser seguidas ex: 1. 2. 3. 4.


    <ol>
         
         <li>1 temp ep:1</li>
         <li>1 temp ep:2</li>
         <li>1 temp ep:3</li>
         <li>1 temp ep:4</li>
         <li>1 temp ep:5</li>
        
     </ol>

 exemplo :         


 1.     priemiro faça isso	
 2.     dps faça isso
 3.     e dps isso
 4.     agr isso
 5.     e por fim isso.
--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
  tag de listas uma embaixo da outras de itens que nao precisam ter ordem. 

      <ul>
          <li>surfe  </li>
          <li>skate  </li>
          <li>jogar  </li>
          <li>estudar</li>
      </ul>



     exemplo  


•surfe
•skate
•jogar
•estudar

--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
<b>   deixar a palavra em negrito ' deixar a palavra mais escura ' 

--------------------------------------------------------------------------------------------------------------------------------------
                
--------------------------------------------------------------------------------------------------------------------------------------
     criação de um formulario < form> 

      
    <form action="envio.php" method="get"  

      ( action) é aonde vamos enviar as informaçoes por exemplo ' envio.php' ou URL, 
vai ser inserido as informaçoes enviadas ao banco de dados( formulario)

--------------------------------------------------------------------------------------------------------------------------------------

( GET  ) estamos RECEBENDO DADOS EM UMA BUSCA DE DADOS pegando informaçoes do banco de dados
( POST ) estamos em um ENVIO DE INFORMAÇOES PARA SALVAR NO BANCO DEDADOS.
--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------------------------------------------
<input type=" text" name="name" >
--------------------------------------------------------------------------------------------------------------------------------------
<input type="submit" value=" Enviar">   botão de enviar, envio para aonde foi direcionado no <form action="envio.exemplo" method="get">
--------------------------------------------------------------------------------------------------------------------------------------


--------------------------------------------------------------------------------------------------------------------------------------
          <input type="radio" name=" sexo"value=' masculino'>Masculino
--------------------------------------------------------------------------------------------------------------------------------------
          <input type="radio" name=" sexo"value=' feminino'>Feminino 
--------------------------------------------------------------------------------------------------------------------------------------
          <input type="radio" name=" sexo"value="outros"> Outro
--------------------------------------------------------------------------------------------------------------------------------------
          exemplo  O masculino  0 feminino  O outro


       preencher alguma.
--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
    <input type="checkbox" name="temcarro"> tenho uma moto

         quadradinho para ser marcado 
--------------------------------------------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------------------------------------------
         data de nascimento <input type="date" name="aniversario">
--------------------------------------------------------------------------------------------------------------------------------------




 escrever um comentario  

<textarea cols="30" rows="10"></textarea>   num quadrado para escrever dentro.

--------------------------------------------------------------------------------------------------------------------------------------


  botão de enviar <input type="submit"value=' enviar'>

--------------------------------------------------------------------------------------------------------------------------------------


  botão desabilitado <button disabled="disabled">não </button>  

--------------------------------------------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------------------------------------------
        mudar cor do fundo css

           body{ background: rgb(44, 57, 82);}

--------------------------------------------------------------------------------------------------------------------------------------


        <input type="password"name=' senha' >digite sua senha 
--------------------------------------------------------------------------------------------------------------------------------------
      <input type="login"name=' logar'> email 
--------------------------------------------------------------------------------------------------------------------------------------
    

        (barrinha ja preenchida de fundo)

       <input type="login"name=' logar'placeholder=' email'>
--------------------------------------------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------------------------------------------
    <input type="login"name=' logar'value=' email'>   ( value )ja da um valor e preeche a barra

--------------------------------------------------------------------------------------------------------------------------------------

   colocar toda  a estrutura dentro de BODYA NO MEIO  e alinhar 

         css
         body{  text-align: center;

--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
   para um preenchemento de campo obrigatorio:  required


 exemplo:  


    <input type="login"name=' logar'placeholder=' email'required >
   
mas para isso deve estar dentro do <form> de formulario exemplo 

<form>

<input type="login"name=' logar'placeholder=' email'required >
<button> enviar </button>

</form>

--------------------------------------------------------------------------------------------------------------------------------------

        para algo que nao pode ser alterado pelo usuario 

<input type="text" name=" sexo"value=' preenchido ' (readonly) =''>

--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
    para desabilitar um click ou uma  opção. 

exemplo


  <button disabled="disabled">não </button>


   para colocar um limite de digitos 
<input type="text"name=' login'  maxlength="5">     ( maxlength) 


--------------------------------------------------------------------------------------------------------------------------------------
   sobre oq é o assunto da pagina 

    <meta name="description" content=" representação da pagina  ">


----------------------------------------------------------------------------------------------------
   /* comentario em CSS \*

----------------------------------------------------------------------------------------------------


para mudar cor por da linha do codigo por class, mais de um codigo.  exemplo 

   class <p class="cor"> larissa</p>


        <p class="cor"> larissa</p>
        <p class="p-texto"> larissa</p>
        <p class="p-texto"> larissa</p>     CSS  .cor{ color: black; } 

----------------------------------------------------------------------------------------------------

para mudar apenas uma unica linha de cor  exemplo  ID=' name '> 


       #cor{  color: rgb(7, 109, 46);}





        <p id="cor"> dede</p> 

        <p class="p-texto"> larissa</p>
        <p class="p-texto"> larissa</p>
        <p class="p-texto"> larissa</p>
----------------------------------------------------------------------------------------------------


   <s> letra cortada </s>

--------------------------------------------------------------------------------------------------------------------------------------

