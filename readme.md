# Copilot + Reconhecimento de textos em imagens
vamos delegar para a IA a tarefa de gerar imagens que contém alguns texto para posteriormente identificar somente esses texto.

## Gerando a imagem
1 - Acesse o <a href="https://copilot.microsoft.com/">Copilot</a> e digite no campo a seguinte frase:<br> 

crie uma imagem com a frase "O segredo do sucesso é ir de fracasso em fracasso sem perder o entusiasmo".

2 - Após a imagem ter sido gerada, entre no <a href="https://portal.azure.com/?azure-portal=true" target="__blank">portal do azure</a>, no menu lateral esquerdo procure a opção de criar um recurso, e logo em seguida selecione o create da opção Azure Al Services.   
3 -  Assim como no laboratorio anterior vamos seguir a documentação oficial e preencher os seguintes campos
<ul>
    <li><b>Resource Group:</b> imagens </li>
    <li><b>Region:</b> East US </li>
    <li><b>Name:</b> labimagens </li>
    <li><b>Princing Tier:</b> Standard SO</li>
</ul> 
<b>Obs:</b> 
<ul>
    <li>- Os campos de <b>Name</b> e <b>Resource Group</b> você pode atribuir os nome da sua preferência</li>
    <li>- Selecione o <b>check box!!</b></li>
</ul>
4 - Após todos os preenchimentos, clique em <b>Review + Create</b> e logo após em <b>Create</b>
5 - Abra o <a href="https://portal.vision.cognitive.azure.com/?azure-portal=true">Azure Vision</a>
6 - clique em todos os recursos, selecione o recurso que acabamos de criar e clique em Select as default resource. Não vai ter nenhum ação e você pode fechar no X superior direito.
<b>Obs:</b> O X mencionado no passo anterior <b>não</b> é o que fecha a aba do navegador

7 - Selecione Reconhecimento óptico de caracteres e logo em seguida extrair texto de imagens.

8 - Selecione o checkbox e clique em procurar um arquivo, logo em seguida, selecione sua imagem.

9 - Após todos seguir todos os passos o texto da imagem surgirá ao lado.

