# Datasets

Os arquivos deste diretório usam como base o [Projeto Machado de Assis: Dataset](https://github.com/ethelbeluzzi/projetomachado).

O arquivo `machado_tokenized_sentences.json` é uma lista de listas de tokens em que as sentenças são maiores que 5 tokens. Sentenças com palavras fora do vocabulário foram removidas. Pontuação é um token separado nas sentenças. No total, há 97.993 sentenças.

O arquivo `machado_vocab.json` contém as 19.999 palavras de maior frequência no texto, mais um marcador de OOV (Out Of Vocabulary) na primeira posição.

O arquivo `machado_word_to_idx.json` contém o mapeamento de cada palavra para seu índice no vocabulário.
