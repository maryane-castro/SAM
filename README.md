<h1 align="center">Segmentation Anything Model (SAM) - META</h1>
<hr>
<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge"/>
</p>

<p>Bem-vindo à documentação do projeto! Neste repositório, você encontrará todas as informações necessárias para entender e usar essa poderosa técnica de segmentação de imagens do META.</p>


<h2>Descrição do Repositório</h2>
<p>A Segmentação de Qualquer Coisa é um campo em rápida evolução dentro da visão computacional, que visa identificar e segmentar objetos específicos em uma imagem. Neste projeto, utilizamos a tecnologia Meta, que é uma abordagem de aprendizado de máquina baseada em modelos de linguagem, para realizar a segmentação de qualquer tipo de objeto em uma imagem.</p>

<p>SAM é um sistema de segmentação com capacidade de receber instruções (promptable) que possui generalização de zero-shot para objetos e imagens desconhecidos, sem a necessidade de treinamento adicional.</p>


<h2>Como Usar</h2>
<p>Embora no Notebook disponibilizado há várias "ajudas", aqui está um tutórial inicial</p>

## Como usar

Siga as instruções abaixo para executar o Segment Anything Model (SAM) e realizar a segmentação automática ou manual de imagens.

### Pré-requisitos

- Python 3.7 ou superior
- GPU compatível com CUDA (recomendado)

### Instalação

1. Clone este repositório para o seu ambiente local.

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Navegue até o diretório do projeto.

```bash
cd seu-repositorio
```

3. Instale as dependências necessárias.

```bash
pip install -r requirements.txt
```

### Segmentação Automática

1. Certifique-se de ter uma imagem de entrada no formato JPEG ou PNG.

2. Execute o seguinte comando para realizar a segmentação automática.

```bash
python segment_auto.py --image caminho/para/imagem.jpg
```

3. O resultado da segmentação automática será exibido na tela ou salvo como um arquivo de imagem.

### Segmentação Manual

1. Certifique-se de ter uma imagem de entrada no formato JPEG ou PNG.

2. Execute o seguinte comando para realizar a segmentação manual.

```bash
python segment_manual.py --image caminho/para/imagem.jpg
```

3. Uma janela interativa será aberta, onde você poderá desenhar uma caixa delimitadora em torno da área que deseja segmentar.

4. Após desenhar a caixa, a máscara correspondente será gerada e exibida na janela.

5. Pressione a tecla "Esc" para fechar a janela e salvar a máscara resultante como um arquivo de imagem.

### Exemplos de Uso

- Segmentação Automática:

```bash
python segment_auto.py --image examples/image1.jpg
```

- Segmentação Manual:

```bash
python segment_manual.py --image examples/image2.jpg
```

Certifique-se de substituir "caminho/para/imagem.jpg" pelos caminhos reais das imagens que você deseja segmentar.






<h2>Contribuição</h2>
<p>Sinta-se à vontade para contribuir para este projeto de Segmentação de Qualquer Coisa com Meta! Se você tiver ideias para melhorias, correções de bugs ou novos recursos, abra uma issue neste repositório. Você também pode enviar um pull request com suas alterações propostas.</p>


<h2>Licença</h2>
<p>Este projeto é licenciado sob a licença <a href="https://opensource.org/license/mit/">MIT LICENCE</a>
. Leia o arquivo LICENSE para obter mais informações sobre os direitos concedidos.</p>

<h2>Contato</h2>


<p>Se você tiver alguma dúvida ou sugestão relacionada a este projeto, sinta-se à vontade para entrar em contato. Você pode me alcançar através do email maryane.castro993@gmail.com</p>
