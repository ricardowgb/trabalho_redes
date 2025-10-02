# trabalho_redes
# Verificador de Rede – IP e Máscara

## Objetivo
Este projeto tem como objetivo verificar se um **IP de destino** pertence à mesma rede de um **IP fixo** (`192.168.1.10`), considerando uma **máscara de sub-rede em bits**.  

É uma ferramenta educativa para auxiliar no estudo de **endereçamento IPv4** e **sub-redes**.

---

## Estrutura do Código
O código está em um único arquivo `index.html`, contendo:

- **HTML** → Estrutura da página.  
- **CSS** → Estilização da interface.  
- **JavaScript** → Lógica de verificação da rede.  

---

## Tecnologias Utilizadas
- **HTML5**  
- **CSS3**  
- **JavaScript (ES6+)**  

---

## Explicação do Código

###  HTML
- Campo para **máscara em bits** (ex: `24`).  
- Campo para **IP de destino** (ex: `192.168.1.50`).  
- Botão **Verificar** que executa a função principal.  
- Área de saída que exibe os resultados.  
- Lista com os integrantes do projeto.  

### CSS
- Define o **layout responsivo e limpo**.  
- `.container` centraliza e estiliza o conteúdo.  
- Botão com cor azul e efeito *hover*.  
- Caixa de resultado com fundo diferenciado.  

### JavaScript
Principais funções:
- **`gerarMascara(bits)`** → Cria a máscara de sub-rede em decimal e binário.  
- **`ipParaInt(ip)`** → Converte um IP em número inteiro para cálculos de rede.  
- **`verificar()`** → Função principal que:
  1. Obtém os valores da máscara e do IP destino.  
  2. Calcula rede de origem e destino.  
  3. Mostra a máscara em decimal e binário.  
  4. Indica se o IP pertence à mesma rede que o IP fixo.  

---

## Como Executar
1. Salve o código em um arquivo `index.html`.  
2. Abra o arquivo em um navegador moderno (Chrome, Edge, Firefox).  
3. Informe:
   - **Máscara em bits** (ex: `24`).  
   - **IP destino** (ex: `192.168.1.50`).  
4. Clique em **Verificar**.  
5. Veja o resultado na tela.  

---

## Exemplo de Saída

### Entrada:
- Máscara: **24**  
- IP destino: **192.168.1.50**  

### Saída:
```
Máscara decimal: 255.255.255.0
Máscara em binário: 11111111 . 11111111 . 11111111 . 00000000
O IP 192.168.1.50 está na MESMA rede de 192.168.1.10.
```

---

## Integrantes
- Hiarley  
- Káthia  
- João Pedro  
- Ricardo  

