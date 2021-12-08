<h1> <center> Projeto - Análise de Dados SIH SUS <a href="#SIHSUS" id="SIHSUSref"> <sup> 1 </sup> </a>  Partos na cidade do Rio de Janeiro </center> </h1>

<p align="center">
<img src="https://img.shields.io/badge/Python-100%25-lightgrey">

 <img>
<a href="https://github.com/datalabe/Projeto_Analise_Eleitoral/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/datalabe/Projeto_Analise_Eleitoral"></a>
</p>


<p> No Rio de Janeiro, parto humanizado ainda é coisa de mulheres ricas e brancas.
  
Enquanto as maternidades tradicionais do SUS carioca (Rede Cegonha) atendem mais mulheres negras do que brancas, os números se invertem na Casa de Parto David Capistrano, a única opção de parto humanizado gratuito no Rio de Janeiro. Conversamos com mães, enfermeiras e médicos para entender o rolê que é o atendimento gestacional humanizado para uma mulher preta.
</p>

#### Reportagem  [PARTOS DA PRETAS](https://datalabe.org/parto-das-pretas/) 








<a id="SIHSUS" href="SIHSUS"> <sup> 1 </sup> </a> Sistema de Internação Hospitalar do Sistema de Saúde Único

  
##  Dados

Foi coletado dados do SIH-SUS de Janeiro de 2019 a Junho de 2020, no qual foi filtrado apenas internações da cidade do Rio de Janeiro e por códigos de procedimentos de parto, dado os 4 tipos de categorias: Humanizado, Rede Cegonha, Universitário, Não Rede Cegonha. O objetivo da análise foi entender como esse dados se comportam em relação a raça, faixa etária e unidade hospitalar.

 - Códigos:
   
0310010039 - Parto normal  
020203109  - Reação de hemaglutinação (TPHA) p/ diagnóstico da siflis   
0310010047 - Parto normal em gestação de alto risco      
0310010055 - Parto normal em centro de parto normal (CPN)   
0411010026 - Parto cesariano em gestação de alto risco   
0411010034 - Parto cesariano   
0411010042 - Parto cesariano com laqueadura tubaria       
0411020048 - Tratamento cirúrgico de gravidez  ectópica     
021401004  - Teste rápido para detecção de HIV em gestante      



 
  - Dados SIH/SUS :point_right: [AQUI](https://divulgacandcontas.tse.jus.br/divulga/#/)
 
 #### Neste repositório você encontra:
                   
                   1. Base de dados 2019 SIH-SUS
                   2. Base de dados 2020 SIH-SUS
                   3.Jupyter Notebook com a limpeza do dados, as análises e comentários
                   4. Relatório da análise
                                  


:nerd_face: | EQUIPE DE DADOS: [Estephany Nunes](https://instagram.com/esteeeephany), [Paulo Mota](https://rpubs.com/polinhobr/679254) e [Samantha Reis](https://github.com/SamanthaReiis)
  
##  Conclusão

   Das 413664 internações registradas nessa janela temporal na cidade do Rio de Janeiro aproximadamente 17% são por procedimentos de partos e nesta os partos normais são mais prevalentes por política do SUS, e tendo em segundo lugar partos cesarianos. Na Rede cegonha e Não Rede Cegonha a maioria dos partos são normais, já os hospitais universitários concentram os partos de maior risco, tem-se por política este encaminhamento via SUS. Na casa de parto, apenas mulheres de baixo risco podem ter seus filhos lá e portanto todas terão parto normal.  
 
 Em todos os hospitais mulheres negras são mais mais prevalente, sem surpresas. Porém foi descoberto  que na única  casa de parto humanizado no Rio  de Janeiro a porcentagem de mulheres brancas é bem superior a de qualquer outro hospital, bem como mulheres pretas tem menor participação neste hospital do que em outros. Isso revela uma falta de acesso, muito provavelmente pela falta de informação e não exclusão, porque todos são SUS.    
 
 Na casa de parto humanizado é onde temos menor participação das faixas etárias fora de 20-34 anos, que seria a de menor risco. As casas de parto tem um apontamento se o parto é de risco ou não pela biologia do corpo da mulher,  aquelas abaixo de 19 e maiores que 35 terão mais riscos de complicação. Isso faz com que o público da casa de parto humanizado seja sempre mais composto pela faixa etária fora das faixas de riscos. Só que mulheres abaixo de 19 anos tendo filhos é um reflexo da ausência de políticas familiares que faz com que meninas engravidem e tenham que realizar o parto. A faixa etária que revela maior planejamento é a de 35 a 49 anos, que em geral é a mulher inserida no mercado de trabalho.  
 
 O total dos partos normais na Casa de Parto David Capistrano é responsável por menos de 1% do total, a não ampliação de estabelecimentos desse perfil torna o parto humanizado e natural um evento extremamente raro, mesmo com a aprovação do projeto de lei que incentivava a inauguração de mais casas de parto. O que explica isso foi a troca no Ministério Saúde e o corporativismo da classe médica no Brasil
  
  <a id="#negros3" href="negros3ref"> <sup> 3 </sup> </a> *A análise considera <u>negros</u>*  *como a soma de pretos e pardos, isto devido o recorte racial que está sendo feito na análise e entendimento da população negra no Brasil por parte da organização.*
  
  
##   Licença

Ao compartilhar este projeto cite os desenvolvedores!

Os dados e scripts podem ser usados e melhorados por qualquer pessoa! Licença MIT
  
  


Gostou desse projeto? Acesse nosso site para mais :wave: [data_labe](https://datalabe.org/)
