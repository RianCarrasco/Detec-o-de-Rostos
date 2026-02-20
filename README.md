# Detec-o-de-Rostos
O projeto usa "ArcFace" e "retianaface" combinados para uma detecção otimizada de rostos de pessoas.

Abra o terminal (ou Anaconda Prompt).

Navegue até a pasta onde descompactou os arquivos.

Execute o comando:
conda env create -f rosto.yml

Após terminar, ative o ambiente:
conda activate nome_do_ambiente_que_esta_no_yml

Use o comando: 
jupyter notebook

Execute o código



O formato dos arquivos devem estar na seguinte forma:

Base de dados:
Imagens conhecidas-> Aqui é a pasta onde você deve colocar a foto da pessoa que você quer procurar, ex: Fernando.png, Ana.png.

Imagens para analisar->Pasta com todas as imagens que seram analisadas

Não encontrados-> Uma pasta para colocar as imagens que não deram metch

Rostos detectados->A pasta de saida na qual tera de forma organizada todas as imagens separadas
