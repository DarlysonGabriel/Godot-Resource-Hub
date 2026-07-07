# Importando arquivos `.res` e `.tres`

## Como importar arquivos `.res` e `.tres`?

Olá! 👋

Neste tutorial, você aprenderá a importar arquivos de configuração `.res` e `.tres` para o projeto.

Leia este guia até o final para evitar erros durante a importação.

---

## 1. Preparação

Antes de começar, certifique-se de que os seguintes requisitos foram atendidos:

* O arquivo deve estar compactado em **`.zip`** ou **`.rar`**.
* O pacote **não deve conter scripts**, como:

  * GDScript (`.gd`)
  * C# (`.cs`)
  * Python (`.py`)
  * Ou qualquer outra linguagem de programação.

Se tudo estiver correto, podemos continuar.

---

## 2. Organização das pastas

Para facilitar a importação, mantenha a estrutura de pastas organizada.

Exemplo:

```text
res://
├── src/
│   ├── config/
│   │   └── water/
│   │       ├── textures/
│   │       │   └── water.png
│   │       └── water.tres
```

> **Importante**
>
> Sempre que possível, utilize nomes de arquivos e pastas em **inglês**.

---

## 3. Compactando os arquivos

Depois de organizar tudo, compacte a pasta em um arquivo `.zip` ou `.rar`.

Exemplo:

```text
res://
├── src/
│   ├── config/
│   │   └── water/
│   │       ├── textures/
│   │       │   └── water.png
│   │       ├── water.tres
│   │       └── water.zip
```

Você deve deixar o arquivo compactado na pasta raiz do seu sistema ou em qualquer local de fácil acesso.

---

## 4. Definindo o caminho do arquivo

Na sua cena, adicione um **Label2D** ou **Label3D** contendo o caminho completo do arquivo compactado.

Exemplo:

```text
res://src/config/water/water.zip
```

O sistema utilizará esse caminho para localizar e importar o pacote.

---

# Antenção:

Caso seu sistema tenha algo a mais, ou tenha que fazer passos extrar, crie uma pasta de `tutorial.md` para especificar os passso a passos 

## Pronto!

Agora, basta dar seu commit e seu push no repositório.
