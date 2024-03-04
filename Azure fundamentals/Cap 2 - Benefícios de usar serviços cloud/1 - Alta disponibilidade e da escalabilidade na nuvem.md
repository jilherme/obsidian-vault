
Ao criar ou implantar um aplicativo de nuvem, duas das maiores considerações são:
* tempo de atividade (ou **disponibilidade**);
* capacidade de lidar com a demanda (ou a **escala**).

## Alta disponibilidade

 É importante que os recursos estejam disponíveis quando necessário. A alta disponibilidade se concentra em garantir a **disponibilidade máxima**, independentemente de interrupções ou eventos que possam ocorrer.

 Ao arquitetar uma solução é preciso considerar as garantias de disponibilidade do serviço.  SLAs (Contratos de Nível de Serviço).

## Escalabilidade

A escalabilidade refere-se à capacidade de **ajustar recursos** para atender à demanda. Se você experimentar um pico repentino de tráfego e seus sistemas ficarem sobrecarregados, a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

Tipos de escala: 
* vertical - concentra em aumentar ou diminuir a capacidade dos recursos.
* horizontal - adição ou subtração do número de recursos.

### Dimensionamento vertical

Pode escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. Por outro lado, se você percebesse que superestimou as necessidades, poderia reduzir verticalmente, diminuindo as especificações.

### Dimensionamento horizontal

Com a escala horizontal, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (**automaticamente** ou **manualmente**). Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. 
Se houver uma queda significativa na demanda, o contrário é válido.

