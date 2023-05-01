# site-escola
HTML
<html>
 <head>  
 </head> 
 <body> 
  <header class="cabecalho"> 
   <img> 
   <h1> Vai ser uma imagem aqui </h1> 
   <ul class="cabecalho-lista-item"> 
    <li class="cabecalho-lista-item">Estudante</li> 
    <li class="cabecalho-lista-item">Escola</li> 
   </ul> 
  </header> 
  <section class="escola"> 
   <div clas="escola-conteúdo"> 
    <h2 class•"escola-titulo">Sobre a escola</h2>  
    <p class="escola-texto-um">texto texto</p> 
   </div> 
  </section>   
 </body>
</html>

.CSS
*{
margin: 0;
padding: 0;
}
.cabecalho{
background-color: #383d58;
color: white;
display: flex;
justify-content:space-around;
padding:24px 0;
}
.cabecalho-lista-item{
display:inline-block;
margin:0 16px;
padding:24px 0;
font-size:24px;
}
.escola{
background-image:linear-gradient(#383d58,#00c0eb);
color:white;
display:flex;
justify-content:center;
align-items:center;
padding:24px 0;
}
.escola-conteudo{
width:35%;
}
.escola-titulo{
padding:24px 0;
}