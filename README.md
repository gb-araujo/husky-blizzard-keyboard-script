# Husky Blizzard 60% Keyboard Script

Script em AutoHotkey para deixar o teclado Husky Blizzard 60% mais confortavel no uso diario, adicionando atalhos para setas direcionais e aspas simples sem depender de combinacoes nativas do teclado.

## Atalhos

| Atalho | Acao |
| --- | --- |
| `RShift + I` | Seta para cima |
| `RShift + J` | Seta para a esquerda |
| `RShift + K` | Seta para baixo |
| `RShift + L` | Seta para a direita |
| `LShift + Esc` | Aspas simples (`'`) |

## Requisitos

- Windows
- [AutoHotkey](https://www.autohotkey.com/)
- Teclado compacto 60% ou layout onde esses atalhos facam sentido

## Como usar

1. Instale o AutoHotkey.
2. Baixe ou clone este repositorio.
3. Execute o arquivo `script.ahk`.
4. Mantenha o script rodando em segundo plano enquanto quiser usar os atalhos.

```bash
git clone https://github.com/gb-araujo/husky-blizzard-keyboard-script.git
cd husky-blizzard-keyboard-script
```

Depois disso, basta abrir `script.ahk` no Windows.

## Gerar executavel

Caso prefira usar sem abrir o arquivo `.ahk` diretamente, compile o script com o Ahk2Exe, ferramenta que acompanha o AutoHotkey.

## Observacoes

- O script foi criado para uso pessoal no teclado Husky Blizzard 60%.
- Se algum atalho conflitar com outro programa, edite as combinacoes diretamente em `script.ahk`.
- Para iniciar com o Windows, adicione um atalho do script ou executavel na pasta de inicializacao do sistema.
