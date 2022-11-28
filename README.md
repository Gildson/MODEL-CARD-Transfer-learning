
As técnicas de Deep Learning requerem um volume imenso de dados para que se possa ajustar os milhões de parâmetros das redes neurais. Entretanto, problemas cotidianos (seja de uma empresa que quer começar a usar IA em seus produtos ou mesmo um projeto acadêmico) não costumam ter essas bases gigantescas.

O segredo então é o uso de uma técnica nomeada _Transfer Learning_. Se um modelo de uma dada tarefa foi treinado num dataset grande e generalista o suficiente, ele será genérico para aquela tarefa. Assim, ele é um bom ponto inicial para o seu. Isso é Transfer Learning.

Esse repositório apresenta um projeto de _Transfer Learning_ aplicado a um exemplo real. Ele foi construído baseado em um exemplo de [Ivanovitch Medeiros](https://github.com/ivanovitchm/embedded.ai/blob/main/lessons/week_10/TransferLearning.ipynb). A pasta `codes` contém os arquivos ordenados seguindo o _workflow_ de Machine Learning. Em suma:
- **Fetch Data**: Download dos dados a partir de uma base de dados externa;
- **Preprocessing**: Processamento necessário para garantir que os dados estejam uniformizados;
- **Segregation**: Separação dos dados nos subconjuntos adequados;

Por fim, a técnica de _Transfer Learning_ é aplicada a duas redes neurais (VGG e Resnet), e cada um desses processos possui um arquivo específico. Cada um desses arquivos demonstra duas maneiras pelas quais _Transfer Learning_ pode ser utilizado. Os resultados para cada rede se encontram no WandB: [VGG](https://wandb.ai/gildson/transfer_learning_VGG-16) e [ResNet](https://wandb.ai/gildson/transfer_learning_ResNet50)

[Um artigo completo referente a esse projeto está disponível no Medium](https://medium.com/@mateus.d.assis.silva/transfer-learning-com-vgg16-e-resnet50-39e58c3e84c3), além de um [vídeo no Loom](https://www.loom.com/share/8a3a65f989204570b893dc33df7db367).
